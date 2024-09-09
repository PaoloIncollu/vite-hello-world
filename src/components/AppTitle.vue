<script>
export default {
  data() {
    return { 
      message: 'La mia prima app con Vite!'
    }
  }
}
</script>

<template>
  <header>
    <h1>
      {{ message }}
    </h1>
  </header>
</template>

<style scoped>
header {
  background-color: blue;
  text-align: center;
  padding: 20px 0;

}

h1 {
  color: greenyellow;
  font-size: 100px;
  
}
</style>
