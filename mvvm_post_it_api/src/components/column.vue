<template>
    <div class="column">
        <h2>{{column_name}}</h2>
        <post_it_note msg="Dans un wagon bleu, tout en mangeant cinq kiwis frais, vous jouez du xylophone." />
        <post_it_note msg="Dans un wagon bleu, tout en mangeant cinq kiwis frais, vous jouez du xylophone." />
    </div>
</template>
<script>
import post_it_note from "./post_it_note.vue";
export default {
    name: 'column',
    props: {
        column_name: String,
    },
    components :{
        post_it_note
    }
};
</script>

<style>
.column
{
    border-radius:10px;
    background: rgb(185, 185, 185);
    margin: 10px;
    padding:10px;
    width:15%;
}
</style>