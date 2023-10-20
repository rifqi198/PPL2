<script setup>
import { ref } from 'vue'

const appName = ref('title')
</script>

<template>
    <div class="navbar">
        <h1 :class="appName">Partimer</h1>
        <div class="nav">
            <p>Find Jobs</p>
            <p>Categories</p>
            <p>Contact Us</p>
            <p>As Company</p>    
        </div>
        <button>Login</button>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cabin&family=Croissant+One&family=Viga&display=swap');
.navbar{
    display: flex;
    color: black;
    padding: 10px 56px;
}
.nav{
    display: flex;
    align-items: center;
}
h1{
    font-family: 'Croissant One', serif;
    font-size: 40px;
}
p{
    margin: 20px;
    font-family: 'Cabin', sans-serif;
    border-bottom: solid black 2px;
}
button{
    font-family: 'Viga', sans-serif;
    justify-content: center;
    align-items: center;
    border: none;
    border-radius: 5px;
    font-size: 24px;
    padding: 10px 49px;
    background-color: #C780FA;
    stroke: none;
}
</style>