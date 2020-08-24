<template>
    <v-container grid-list-lg>
        <v-layout row>
            <v-flex xs12 class="text-xs-center display-1 font-weight-black my-5">About Us</v-flex>
        </v-layout>
        <v-layout justify-center align-center row wrap>
            <v-flex xs12 sm12 md4>
                <v-card class="rounded-xl">
                    <v-img src="http://source.unsplash.com/Q1p7bh3SHj8" height="500px">
                        <v-container fill-height fluid>
                            <v-layout fill-height>
                                <v-flex xs12 align-end flexbox>
                                    <v-col>
                                        <span class="headline white--text">Patrik Sohlman</span>
                                    </v-col>
                                    <v-col>
                                        <v-btn right fab class="white darken-4">
                                            <v-icon>mdi-github</v-icon>
                                        </v-btn>
                                    </v-col>
                                </v-flex>
                            </v-layout>
                        </v-container>
                    </v-img>

                    <v-card-title primary-title>
                        <div>
                            <h3 class="headline mb-0">IoT and Cloud solutions developer</h3>
                            <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam mauris felis, varius rutrum massa a, dignissim ornare dui. Cras eget velit eu dui tristique lobortis sit amet vel tellus.
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>

            <v-flex xs12 sm12 md4>
                <v-card class="rounded-xl">
                    <v-img src="http://source.unsplash.com/w7ZyuGYNpRQ" height="500px">
                        <v-container fill-height fluid>
                            <v-layout fill-height>
                                <v-flex xs12 align-end flexbox>
                                    <v-col>
                                        <span class="headline white--text">Alexander Sundberg</span>
                                    </v-col>
                                    <v-col>
                                        <v-btn right fab class="white darken-4">
                                            <v-icon>mdi-github</v-icon>
                                        </v-btn>
                                    </v-col>
                                </v-flex>
                            </v-layout>
                        </v-container>
                    </v-img>
                    <v-card-title primary-title>
                        <div>
                            <h3 class="headline mb-0">Full stack developer, API Guru</h3>
                            <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam mauris felis, varius rutrum massa a, dignissim ornare dui. Cras eget velit eu dui tristique lobortis sit amet vel tellus.
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>

        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'AboutUs'
};
</script>

<style scoped>
</style>