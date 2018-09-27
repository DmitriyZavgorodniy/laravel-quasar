<template>
    <div>
        <q-toolbar color="blue-grey-14">
            <q-toolbar-title>
                <span>Laravel with Quasar Framework (SPA) by Manfred047</span>
            </q-toolbar-title>
            <lang-manager></lang-manager>
            <q-btn flat
                   dense
                   label="See 404"
                   @click="$router.replace({name: 'e404'})">
            </q-btn>
            <q-btn flat
                   dense
                   label="Guest"
                   @click="$router.replace({name: 'user.index'})">
            </q-btn>
        </q-toolbar>
    </div>
</template>

<script>
    import LangManager from "../LangManager";
    export default {
        name: 'welcome-toolbar',
        components: {
            LangManager
        }
    }
</script>
