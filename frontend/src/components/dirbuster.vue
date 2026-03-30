<script setup>
import {reactive} from 'vue'
import {Greet} from '../../wailsjs/go/main/App'



</script>

<template>
  <main>
    <p><span class="dollar">$</span> dirbuster:</p>
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
