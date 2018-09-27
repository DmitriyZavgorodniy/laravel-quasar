<template>
    <div>
        <q-toolbar color="blue-grey-14">
            <q-toolbar-title>
                <span>Laravel with Quasar Framework (SPA) by Manfred047</span>
            </q-toolbar-title>
            <lang-manager></lang-manager>
            <q-btn flat
                   dense
                   label="Go to Welcome"
                   @click="$router.replace({name: 'public.index'})">
            </q-btn>
            <q-btn flat
                   dense
                   label="Guest">
            </q-btn>
        </q-toolbar>
    </div>
</template>

<script>
    import LangManager from "../LangManager";
    export default {
        name: 'user-toolbar',
        components: {
            LangManager
        },
    }
</script>
