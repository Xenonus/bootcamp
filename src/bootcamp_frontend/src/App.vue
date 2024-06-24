<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <h1>
      Gaming
    </h1>
    <br>
    Num: {{ i }}
    </br>
    <button @click="increment">Increment</button>

  </main>
</template>
<script>
export default {
  data() {
    return {
      i: 0
    }
  },
  methods: {
    increment() {
      this.i++
    }
  },
}
</script>
