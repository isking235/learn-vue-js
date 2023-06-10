<template>
  <dv>
    <app-header></app-header>
  </dv>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
// new Vue({
//   data:{

//   }
// })
export default {
  data: function() {
    return {
      str:'hi'
    }
  },
  components:{
    'app-header' : AppHeader
  }
}
</script>

<style>

</style>