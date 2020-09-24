<template>
  <div class="md:grid md:grid-cols-12 text-gray-400 ">
    <TopBar class="md:hidden sticky top-0" @sidebar="showSidebar" />
    <SideBarMobile :isHidden="!isSidebarVisible" class="fixed top-0 md:hidden transform transition-transform duration-300" :class="!isSidebarVisible ? '-translate-x-16' : null" @hidesidebar="hideSidebar" />
    <SideBar class="md:col-span-1 hidden md:flex" />
    <Nuxt class="md:col-span-11 mx-2 md:m-0" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class Default extends Vue {
  isSidebarVisible: boolean = false

  showSidebar () {
    this.isSidebarVisible = true
  }

  hideSidebar () {
    this.isSidebarVisible = false
  }
}
</script>

<style>
</style>
