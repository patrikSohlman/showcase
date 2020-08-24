<template>
    <v-app>
        <app-navigation></app-navigation>
        <home-image></home-image>
        <about-us></about-us>

        <v-content transition="slide-x-transition">
            <router-view></router-view>
        </v-content>
    </v-app>
</template>

<script>
import AppNavigation from '@/components/AppNavigation';
import HomeImage from '@/components/HomeImage';
import AboutUs from '@/components/AboutUs'
export default {
    name: 'App',
    components: {
        AppNavigation,
        HomeImage,
        AboutUs
    }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Code+Pro');
html, body {
  font-family: 'Source Code Pro', monospace;
}

#app {
  font-family: 'Source Code Pro', monospace;
}
</style>