<script setup>
import {reactive} from 'vue'
import {Greet} from '../../wailsjs/go/main/App'

// const data = reactive({
//   name: "",
//   resultText: "Please enter your name below 👇",
// })

// function greet() {
//   Greet(data.name).then(result => {
//     data.resultText = result
//   })
// }

</script>

<template>
  <main>
    <p><span class="dollar">$</span> nmap:</p>
    <hr>
    <label for="flags">Flags:</label>
    <input type="text" id="flags" name="flags" value="-sC -sV -vv -Pn">
    <p>Command: nmap $flags $ip</p>
    <code>Ready.</code>
    <button class="green">Run</button>
  </main>
</template>

<style scoped>
main {
  background-color: var(--fg);
}

.dollar {
  color: var(--accent);
  font-weight: bold;
}

</style>
