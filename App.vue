<template>
  <view class="container">
    <text class="text-color-primary">My Vue Native App</text>
    <text>{{ msg }}</text>
  </view>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      msg: 'This is a msg loaded from VueData Object'
    }
  }
}
</script>


<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: blue;
}
</style>
