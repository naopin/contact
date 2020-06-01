<template>
  <div>
    <h1>HelloWorld</h1>
    <button @click="increment">1</button>
  </div>

</template>



<script>
export default {
  methods: {
    increment() {
      this.$store.commit("increment",2);
    }
   
  }
};
</script>