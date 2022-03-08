<template>
  <div class="main-layout">
    123 123 {{ i }}
    {{ change('123') }}
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent ({
  props: {},
  data () {
    return {
      i: 0
    }
  },
  methods: {
    change (i: number) {
      this.i = i
    }
  }
})
</script>

<style lang="scss">
.main-layout {
  width: 100vw;
  height: 100vh;
}
</style>
