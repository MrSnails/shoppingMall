<template>
  <div flex="main:center cross:center" style="width: 100%;">
    <span flex="cross:center">
      <i class="iconfont icon-weixiuzhong c_hui"></i>
      <span class="m-l f_22 c_hui">建设中……</span>
    </span>
  </div>
</template>

<script>
  import {mapState} from 'vuex'
  export default {
    data () {
      return {}
    },
    methods: {},
    components: {},
    computed: {
      ...mapState({})
    }
  }
</script>

<style scoped>
  div {
    top: 40%;
    position: absolute;
    transform: translate3d(0, -50%, 0)
  }
  i {
    font-size: 60px;
  }
</style>