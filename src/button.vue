

<!--
 * @Description: This is a XX file
 * @Author: JeanneWu
 * @Date: 2020-06-24 11:28:57
--> 


<template>
  <button class="g-button">Hi</button>
</template>
<script type="text/ecmascript-6">
export default {
  data() {
    return {};
  },
  mounted() {},
  methods: {}
};
</script>
<style scoped lang="scss">
.g-button {
  font-size: var(--font-size);
  height: var(--button-height);
  padding: 0 1em;
  border-radius: var(--border-radius);
  border: 1px solid var(--border-color);
  background: var(--button-bg);
  &:hover {
    border-color: var(--border-color-hover);
  }
  &:active {
    background-color: var(--button-active-bg);
  }
  &:focus {
    outline: none;
  }
}
</style>