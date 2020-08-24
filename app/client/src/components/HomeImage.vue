<template>
    <v-container fluid fill-height class="home-image" style="max-height: 100vh;">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center mb-3">Just two friends coding what we feel like</div>
            <div class="display-1 font-weight-bold white--text text-xs-center">A site for your curious eyes, and a site for our curious minds.</div>
            <v-btn fab class="mt-5 white darken-4">
            <v-icon>mdi-arrow-expand-down</v-icon>
            </v-btn>
            
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeImage'
};
</script>

<style scoped>
.home-image {
    background: url('http://source.unsplash.com/9drS5E_Rguc');
    background-size: cover;
    width: 100%;
    min-height: 100%;
}
</style>