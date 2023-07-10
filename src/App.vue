<template>
  <div class="wrapper">
    <MainHeader/>
    <CounterTop/>
    <CounterMain/>
  </div>
</template>

<script>

import MainHeader from "@/components/MainHeader.vue";
import CounterTop from "./components/CounterTop.vue";
import CounterMain from './components/CounterMain.vue';

  export default {
    components: {
    MainHeader,
    CounterTop,
    CounterMain
}
  }
</script>

<style lang="scss" scoped>

</style>