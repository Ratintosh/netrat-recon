<script setup>
import {reactive} from 'vue'
import {Greet} from '../../wailsjs/go/main/App'

</script>

<template>
  <main>
    <img class="logo" src="../assets/images/netrat-blu.png" width="64px">
    <div class="middle">
      <p>Target: 0.0.0.0<a class="edit-link">(edit)</a></p>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: var(--fg);
  padding:5px;
  display:flex;
  align-items: center;
  position: relative;
}
.logo {
  margin-left: 8px;
  z-index: 2;
}
.middle {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  text-align: center;
}
.middle p { margin: 0; }
.result {
  height: 20px;
  line-height: 20px;
  margin: 1.5rem auto;
}

.input-box .btn {
  width: 60px;
  height: 30px;
  line-height: 30px;
  border-radius: 3px;
  border: none;
  margin: 0 0 0 20px;
  padding: 0 8px;
  cursor: pointer;
}

.input-box .btn:hover {
  background-image: linear-gradient(to top, #cfd9df 0%, #e2ebf0 100%);
  color: #333333;
}

.input-box .input {
  border: none;
  border-radius: 3px;
  outline: none;
  height: 30px;
  line-height: 30px;
  padding: 0 10px;
  background-color: rgba(240, 240, 240, 1);
  -webkit-font-smoothing: antialiased;
}

.input-box .input:hover {
  border: none;
  background-color: rgba(255, 255, 255, 1);
}

.input-box .input:focus {
  border: none;
  background-color: rgba(255, 255, 255, 1);
}

.edit-link {
  color: var(--accent);
  font-size: 0.9em;
  margin-left: 8px;
  text-decoration: none;
}

.edit-link:hover {
  cursor:pointer;
}
</style>
