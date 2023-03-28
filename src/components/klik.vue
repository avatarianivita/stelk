<template>
  <div>
    <h1>{{ count }}</h1>
    <button @click="decrement">-</button>
    <button @click="increment">+</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    };
  },
  methods: {
    decrement() {
      this.count--;
    },
    increment() {
      this.count++;
    }
  }
};
</script>

<style>
h1 {
  font-size: 2em;
  text-align: center;
}

button {
  widht: .0em;
  padding: 1.0em;
  font-size: 1.0em;
  margin: 0.5em;
}
</style>