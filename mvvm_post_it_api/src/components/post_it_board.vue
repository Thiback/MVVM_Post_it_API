<template>
    <div id="displays">
        <h1>display case</h1>
        <h2>{{ msg }}</h2>
        <post_it />
        <post_it />
    </div>
</template>

<script>
    import post_it from "./post-it.vue";
    export default {
        name: 'post_it_board',
        props: {
        msg: String,
        components: {
            post_it
        }
    }
}
</script>

<style>
</style>