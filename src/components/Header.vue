<template>
  <div class="hello">
    <p>在线等一个五黑</p>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello > p {
  font-weight: bold;
}
</style>
