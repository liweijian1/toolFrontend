<script setup lang="ts">
import {useRouter} from 'vue-router'

let router = useRouter()
const handleInto = ()=>{
  router.push('/about')
}

</script>

<template>
  <main>
    <div @click="handleInto" class="homeMenu">欢迎来到我的世界</div>
  </main>
</template>
<style>
.homeMenu{
  cursor: pointer;
}
</style>
