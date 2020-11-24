<template>
    <div class="post_it_board">
        <column column_name="Done"></column>
        <column column_name="In progress"></column>
        <column column_name="To-do"></column>
        <column column_name="Ideas"></column>
        <add_column_button/>
    </div>
</template>

<script>
    import column from "./column.vue";
    import add_column_button from "./add_column_button.vue";
    export default {
        name: 'post_it_board',
        props: {
            msg: String,
        },
        components: {
            column,
            add_column_button
        }
}
</script>
<style lang="scss">
.post_it_board
{
  border-radius: 10px;
  border: solid 1px black;
  background: #e9e9e9;
  padding: 20px;
  display:flex;
  flex-direction: row;
  box-shadow: 5px 5px 10px 2px red;
  height:750px;
}
</style>