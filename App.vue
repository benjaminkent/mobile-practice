<template>
  <view class="container">
    <Header />
    <text class="text-color-primary">can I change stuff</text>
  </view>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: "App",
  components: { Header }
}
</script>


<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: flex-start;
}

.text-color-primary {
  color: green;
}
</style>
