<template>
  <div>
    <p class="card">
      {{ text.arr }} <br/>

      <!-- text.arr 为undefined 这里会报错 -->
      <!-- {{ text.arr.length }} -->

      {{ text1 }}
    </p>
  </div>
</template>

<script>
export default {
  props: {
    text: {
      type: Object,
      // 如果在使用组件时，不传递属性，默认值是起作用的。
      default: () => ({
        name: 'ssss',
        arr: [35]  // 默认值不会显示。
      })
    },
    text1: {
      type: String,
      default: 'rrrrr'
    }
  }
}
</script>

<style>
.card {
  padding: 10px;
}
</style>
