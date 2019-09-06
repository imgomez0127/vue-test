<template>
    <div id="app">
        {{Title}}
    </div>
</template>

<script>
export default {
    name: 'app',
    components: {},
    data(){
        return {
            Title: "Todo App",
            todos: [
                {
                    id:1,
                    task:"Eat food",
                    completed:True 
                }
            ]
        } 
    }
}
</script>

<style>
* {
    box-sizing: border-box;
    margin:0;
    padding: 0;
}
</style>
