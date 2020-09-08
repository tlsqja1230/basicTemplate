<template>
    <v-container grid-list-xl fluid>
        <v-layout row wrap class="layout_dashboard">
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'Dashboard',
    components: {
    },
    props: {
    },
    watch: {
    },
    computed: {
    },
    data() {
        return {
        }
    },
    beforeRouteEnter (to, from, next) {
        next()
    },
    created() {
    },
    mounted() {
    },
    updated() {
    },
    methods: {
    },
}
</script>
<style scoped>
.layout_dashboard {
    padding: 20px;
}
</style>