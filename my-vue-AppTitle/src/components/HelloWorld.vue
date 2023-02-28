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
  <div class="bg-blu">
    <h1>
      {{ message }}
    </h1>
  </div>
</template>

<style>
.bg-blu {
  background-color: blue;
  color: white;
}
</style>