<template>
  <div class="main-layout" >
    <Header />
    123 122sdas323 {{ i }}
    {{ change('123') }}
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Header from '@/components/Header.vue'

let age: string | number = '30'

export default defineComponent ({
  props: {},
  components: {
    Header
  },
  data () {
    return {
      i: 0 as number | string 
    }
  },
  methods: {
    change (i: number | string) {
      this.i = i
    }
  },
  created () {
    // this.axios.get('https://api.unsplash.com/photos/random')  
    // this.axios.get('https://api.unsplash.com/photos/:id')  
  }
})
</script>

<style lang="scss">
.main-layout {
  width: 100vw;
  height: 100vh;
  background: url('https://images.unsplash.com/photo-1542451542907-6cf80ff362d6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1521&q=80');
}
</style>
