<template>
    
    <header class="header">
        <h1 v-on:click="easteregg">Victor's Vue Playground</h1>
    </header>

</template>

<script>
export default {
    name: 'Header',
    // el: '#header',
    // // data: {
    // //     name: '69420'
    // // },

    methods: {
        greet: function () {
            alert(`Du fant easteregget! ${this.name} :D`);
        }
    },
    
}


</script>

<style scoped> 
    .header {
        display: flex;
        
        background: #09111f;
        color: #fff;

        height: 10vh;
        width: 100vw;
        
        font-size: 2.5rem;
        
        justify-content: center;
        align-items: center;
    }

</style>