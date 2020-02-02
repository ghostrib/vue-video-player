<template>
  <div>
    <input type="text" @input="handleChange" />
  </div>
</template>

<script>
export default {
  name: "SearchBar",
  methods: {
    handleChange: function(event) {
      alert(event.target.value);
    }
  }
};
</script>

<style scoped>
</style>