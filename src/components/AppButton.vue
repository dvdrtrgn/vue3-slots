<!-- https://vueschool.io/lessons/using-slots -->

<template>
  <strong>
    Some text!
    <button v-bind="$attrs">
      <slot></slot>
    </button>
  </strong>
</template>

<script>
export default {
  inheritAttrs: false, // use false (and bind) to control who gets attrs
};
</script>

<style>
#red {
  color: red;
}
</style>
