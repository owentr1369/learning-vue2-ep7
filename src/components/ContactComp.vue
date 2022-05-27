<template>
  <div>
    <h1>My address: {{ address }}</h1>
    <button v-on:click="changePhone">Show My Phone</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      address: "lo 3b cc Phu tho lu gia p15 q11",
    };
  },
  methods: {
    changePhone: function () {
      this.address = "1234567890";
    },
  },
};
</script>

<style>
</style>