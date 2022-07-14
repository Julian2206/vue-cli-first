<template>
  <div class="message">
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
.message {
  color: yellowgreen;
  font-size: 35px;
  font-weight: bold;
}
</style>
