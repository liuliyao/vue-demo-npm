<template>
  <div class="title-container" :style="eleStyle">
    <div class="title">{{ title }}</div>
  </div>
</template>

<script>
export default {
  name: 'Title',
  components: {},
  props: {
    title: {
      type: String,
      default: ''
    },
    eleStyle:{
      type: Object,
      default: () => {}
    }
  },
  data() {
    return {}
  },
  created() {},
  methods: {}
}
</script>

<style lang="scss" scoped>
.title{
    padding: 0 10px;
    margin-bottom: 10px;
    border-left: 5px solid #3dabc2;
    font-size: 15px;
    font-weight: 700;
    color: #333;
}
</style>
