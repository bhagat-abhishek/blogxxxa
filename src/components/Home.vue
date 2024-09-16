<template>
    <h1>if else Conditions</h1>

    <h3 v-if="show">if Condition</h3>
    <h3 v-else>else</h3>

    <button v-on:click="show=!show" >Show</button>    
    
    
</template>

<script>
export default {
    name: 'Home',
    data() {
        return {
            show: false
        }
    }
}
</script>

<style scoped>
h1 {
    color: #f69;
}
</style>