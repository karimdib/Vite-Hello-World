<script >
export default{
  data(){
    return{
      messaggio:'La mia prima app con Vite!'
    }
  }
}
</script>

<template>
  <div>
    <h1 class="hello">{{ messaggio }}</h1>
  </div>
</template>

<style>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.hello{
  color: greenyellow;
}
</style>
