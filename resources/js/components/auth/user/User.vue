<template>
    <q-page>
        <h1>{{ $t('welcome.greetings') + " guest" }}</h1>
    </q-page>
</template>

<script>
    import { mapGetters} from 'vuex'
    export default {
        name: "user",
    }
</script>

<style scoped>

</style>
