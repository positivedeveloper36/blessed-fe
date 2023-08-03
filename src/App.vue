<script>
  export  default {
    data() {
      return {
        message: 'Hi world',
        count: 0,
      }
    },
    methods: {
      addCount() {
        this.count += 2
      }
    }
  }
</script>

<template>
  <div>{{ message }}</div>
  <span :title='message'>chelsea</span>
  <div>{{ count }}</div>
  <button @click="count++">Add 1</button>
  <button @click="addCount">Add count</button> <br />
  <input type="text" v-model="count" /> <br />
<!--  <input type="text" :value="count" @input="count=$event.target.value" />-->
</template>