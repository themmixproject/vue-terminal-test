<template>
    <terminal-window></terminal-window>
</template>

<script>
import TerminalWindow from "./components/TerminalWindow.vue";
export default {
    name: "App",
    components: {
        TerminalWindow,
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
