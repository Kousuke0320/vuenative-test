<template>
  <view class="container">
    <view class="main">
      <text-input />
    </view>
  </view>
</template>
 
<script>
    import TextInput from './src/todo.vue';
  export default {
    components: {
      TextInput
    }
  }
</script>

<style>
.container {
  background-color: #333;
  flex: 1;
  padding-top: 40px;
  align-items: center;
}
.main {
  flex: 1;
  max-width: 400px;
  align-items: center;
}
</style>
