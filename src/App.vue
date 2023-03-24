<template>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
    name: "App",
    components: {
        HelloWorld,
    },
};
</script>

<style>
body {
    margin: 0;
    padding: 0;
    background-color: black;
    color: white;
    font-family: "Courier New", Courier, monospace;
}

input {
    border: 0;
    font-family: "Courier New", Courier, monospace;
    font-size: inherit;
    padding: 0;
    outline: 0;
    background-color: black;
    color: white;
}
</style>
