<template>
    <div class="post_it_board">
        <h1>display case</h1>
        <post_it_note :msg="msg" />
        <post_it_note msg="titi" />
        <h2>{{ msg }}</h2>

    </div>
</template>

<script>
    import post_it_note from "./post_it_note.vue";
    export default {
        name: 'post_it_board',
        props: {
            msg: String,
        },
        components: {
            post_it_note
        }
}
</script>
.post_it_board
{
  border-radius: 25px;
  background: #73AD21;
  padding: 20px;
  width: 200px;
  height: 150px;
}
<style>
</style>