<template>
    <div class='links'>
            <a class='navbar-item' v-on:click="scroll('landing')">Home</a>
            <a class='navbar-item' v-on:click="scroll('about')">About</a>
            <a class='navbar-item' v-on:click="scroll('work')">Work</a>
            <a class='navbar-item' v-on:click="scroll('contact')">Contact</a>
        </div>
</template>

<script>
export default {
    methods: {
        scroll(id){
            let elmnt = document.getElementById(id);
            elmnt.scrollIntoView({
                behavior: 'smooth'
            })
        }
    }
}
</script>

<style scoped>
    .links{
        position: sticky;
        top: 0;
        width: 100%;
        overflow: hidden;
        z-index: 3;
        display:flex;
        justify-content: space-around;
        background-color: black;
    }

    .links > a{
        text-decoration: none;
        color: white;
        display: block;
        padding: 15px 15px;
        font-size: 0.9em;
        cursor: pointer;
    }

    .links > a:hover{
        background:#1d1d1d;
    }
</style>

