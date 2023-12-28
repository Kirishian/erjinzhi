<template>
  <div>
   <element-view></element-view>
  </div>
</template>

<script>
import ElementView from './views/element/ElementView.vue'
export default {
  components: { ElementView },
 data() {
  return {
     message: "hello vue"
  }
 },
 methods:{

 }
}
</script>
<style>

</style>
