<script setup lang="ts">
import zhCn from 'element-plus/lib/locale/lang/zh-cn'
</script>

<template>
  <el-config-provider
    size="default"
    :zIndex="3000"
    :locale="zhCn"
    :button="{ autoInsertSpace: false }"
  >
    <router-view />
  </el-config-provider>
</template>

<style lang="scss">
html,
body,
#app {
  height: 100%;
}
</style>
