<script setup>
import navbar from './components/nav.vue'
import nmap from './components/nmap.vue'

import dirbuster from './components/dirbuster.vue'
</script>

<template>
  <div class="grid">
    <div class="nav">
      <navbar/>
    </div>
    <div class="left pane">
      <nmap/>
    </div>
    <div class="right pane">
      <dirbuster/>
    </div>
  </div> 
</template>

<style>

</style>
