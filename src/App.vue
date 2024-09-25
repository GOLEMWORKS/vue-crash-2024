<script>
    export default{
      data() {
        return {
          name: 'Иван Иванов',
          status: true,
        }
      }
    }
</script>

<template>
  <h1>Hello {{name}}!</h1>
  <p v-if="status">User is active</p>
  <p v-else="status">User is innactive</p>
</template>
