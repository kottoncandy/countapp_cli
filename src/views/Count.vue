<template>
  <div class="count">
    <h1>カウンターページ</h1>

    <p>{{ count }}</p>

    <p>
      <button @click="increment">+</button>
      <button @click="decrement">-</button>
    </p>
  </div>
</template>


<script>
export default {
  data() {
    return {
      count: "0"
    };
  },
  methods: {
    increment() {
      this.count++;
    },
    decrement() {
      this.count--;
    }
  }
};
</script>
