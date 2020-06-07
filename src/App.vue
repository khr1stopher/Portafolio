<template>
    <div class="app" id="app">
        <barra/>
        <div class="container">
            <router-view/>
        </div>
    </div>
</template>
<script>
import barra from '@/components/barra.vue'

export default {
    components: {
    barra
  }
}
</script>
<style>
.app{
    min-height: 100vh;
}
</style>
