<script lang="ts" setup>
import {btnOptions} from '@/views/common/options'
</script>
<template>
  <div class="about">
    <Button v-for="item in btnOptions" :key="item.value" :type="item.type">{{ item.name }}</Button>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
