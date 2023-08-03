<script>
  export  default {
    data() {
      return {
        message: 'Hi world'
      }
    }
  }
</script>

<template>
  <div>{{ message }}</div>
  <span :title='message'>chelsea</span>
</template>