<template>
  <div id="app">
    
    <page-footer></page-footer>
    <h1>{{title}}</h1>
    
  </div>
</template>

<script>

import PageFooter from './components/PageFooter.vue'

export default {
  name: 'App',
  data() {
    return{
      title: 'Vivo dentro de Vue'
    }
  },
  components: {
   PageFooter
  }
}
</script>

