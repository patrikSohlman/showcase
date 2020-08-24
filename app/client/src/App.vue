<template>
    <v-app>
        <app-navigation></app-navigation>
        <home-image></home-image>

        <v-content transition="slide-x-transition">
            <router-view></router-view>
        </v-content>
    </v-app>
</template>

<script>
import AppNavigation from '@/components/AppNavigation';
import HomeImage from '@/components/HomeImage';
export default {
    name: 'App',
    components: {
        AppNavigation,
        HomeImage
    }
};
</script>

<style>
</style>