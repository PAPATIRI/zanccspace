<script lang="ts" setup>
import Sidebar from './ui/sidebar/Sidebar.vue'
import SidebarContent from './ui/sidebar/SidebarContent.vue'
import SidebarGroup from './ui/sidebar/SidebarGroup.vue'
import SidebarGroupContent from './ui/sidebar/SidebarGroupContent.vue'
import SidebarGroupLabel from './ui/sidebar/SidebarGroupLabel.vue'
import SidebarHeader from './ui/sidebar/SidebarHeader.vue'
import SidebarMenu from './ui/sidebar/SidebarMenu.vue'
import SidebarMenuItem from './ui/sidebar/SidebarMenuItem.vue'
</script>

<template>
  <Sidebar variant="floating">
    <SidebarContent>
      <SidebarHeader>ZANCCSPACE</SidebarHeader>
      <SidebarGroup>
        <SidebarGroupLabel>Hobby</SidebarGroupLabel>
        <SidebarGroupContent>
          <SidebarMenu>
            <SidebarMenuItem>
              <RouterLink to="/">Home</RouterLink>
            </SidebarMenuItem>
            <SidebarMenuItem>
              <RouterLink to="/about">About</RouterLink>
            </SidebarMenuItem>
          </SidebarMenu>
        </SidebarGroupContent>
      </SidebarGroup>
    </SidebarContent>
  </Sidebar>
</template>
