<template>
  <div class="e-colorPicker-demo">
    <h2 class="title_h2 is20">ColorPicker 颜色选择器</h2>
    <p>用于颜色选择</p>
    <h3 class="title_h3">基础用法</h3>
    <div class="e-vue-demo-block">
      <div class="e-vue-source">
        <evue-form v-model="obj" :option="option"></evue-form>
      </div>
    </div>

  </div>
</template>

<script>
  import Index from './index';

  export default Index;
</script>

