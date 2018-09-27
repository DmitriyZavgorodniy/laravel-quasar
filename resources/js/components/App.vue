<template>
    <q-layout view="lHh Lpr fff">
        <q-layout-header>
            <router-view name="top-menu"></router-view>
        </q-layout-header>
        <q-page-container>
            <router-view></router-view>
        </q-page-container>
        <router-view name="app-footer"></router-view>
    </q-layout>
</template>

<script>
    export default {
        name: "app"
    }
</script>

<style scoped>

</style>
