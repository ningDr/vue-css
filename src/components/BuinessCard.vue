<template>
  <div class="md:flex bg-white rounded-lg p-6">
      <img class="h-16 w-16 md:h-24 md:w-24 rounded-full mx-auto md:mx-0 md:mr-6" src="../assets/img/17.jpg"/>
      <div class="text-center md:text-left">
          <h2 class="text-lg">Erin Lindford</h2>
          <div class="text-purple-500">Customer Support</div>
          <div class="text-gray-600">erinlindford@example.com</div>
          <div class="text-gray-600">(555) 765-4321</div>
      </div>
  </div>
</template>
<script>
export default {
  name: "BuinessCard",
  props: {},
  data() {
    return {};
  },
  mounted() {
      console.log("加载了一次...");
  },
  methods: {}
};
</script>
<style scoped>
</style>