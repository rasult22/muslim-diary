<template>
  <div class="main-layout">
    123 123 {{ i }}
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
  }
})
</script>

<style lang="scss">
.main-layout {
  width: 100vw;
  height: 100vh;
}
</style>
