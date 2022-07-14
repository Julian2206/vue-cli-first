<template>
  <div>
    {{ msg }}
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style lang="scss">
div {
  color: royalblue;
  font-size: 25px;
  font-weight: bold;
}
</style>
