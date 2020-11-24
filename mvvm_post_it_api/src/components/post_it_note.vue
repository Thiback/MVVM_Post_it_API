<template>
<div>
    <h2>one post it</h2>
    <span>{{ msg }}</span>
</div>
</template>

<script>
    export default {
        name: 'post_it_note',
        props: {
            msg: String
        }
}
</script>

<style>
</style>