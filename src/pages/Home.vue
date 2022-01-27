<script lang="ts" setup name="homepage">
import { NLayout, NLayoutContent, NLayoutFooter, NLayoutHeader, NSpace } from 'naive-ui';
</script>

<template>
  <n-layout :native-scrollbar="false">
    <!-- header -->
    <n-layout-header class="bg-red-300 sticky">
      <n-space justify="center">
        <h1>Header</h1>
      </n-space>
    </n-layout-header>

    <!-- content -->
    <n-layout-content class="h-screen">
      <h1>Content</h1>
    </n-layout-content>

    <!-- footer -->
    <n-layout-footer class="bg-white">
      <n-space justify="center">
        <h1>Footer</h1>
      </n-space>
    </n-layout-footer>
  </n-layout>
</template>
