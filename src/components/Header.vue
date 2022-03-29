<template>
  <div class="app-header">
    <div class="app-header__left">
      left
    </div>
    <div class="app-header__center">
      center
    </div>
    <div class="app-header__right">
      right
    </div>
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent ({

})
</script>
<style lang="scss">
@import "../scss/colors.scss";
.app-header {
  width: 100%;
  height: 50px;
  background-color: $color-4;
  display: flex;
  &__left {
    
  }
  &__center {

  }
  &__right {

  }
}
</style>