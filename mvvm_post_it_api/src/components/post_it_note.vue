<template>
<div class="post_it_note">
    <h3>one post it</h3>
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


.post_it_note
{
    background:#ffea2d;
    box-shadow: 5px 5px 5px #696800;
    margin-top: 10px;
    padding-left: 3px;
    padding-right: 4px;
    font-size: 1em;
}
</style>