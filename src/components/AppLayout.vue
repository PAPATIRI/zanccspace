<script setup lang="ts">
import SidebarProvider from './ui/sidebar/SidebarProvider.vue'
import AppSidebar from '@/components/AppSidebar.vue'
import SidebarTrigger from './ui/sidebar/SidebarTrigger.vue'
</script>

<template>
  <SidebarProvider>
    <AppSidebar />
    <main>
      <SidebarTrigger />
      <slot />
    </main>
  </SidebarProvider>
</template>
