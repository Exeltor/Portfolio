<template>
  <div class="min-h-full">
    <div class="h-screen/5 flex flex-col justify-center text-center">
      <h1 class="text-5xl font-bold text-green-400 leading-tight">
        My Skills
      </h1>
    </div>
    <div class="flex flex-row justify-center mb-5">
      <button
        class="border rounded rounded-r-none p-5 font-bold transition-colors duration-100"
        :class="selectedTab === 0 ? 'bg-green-500' : null"
        @click="selectedTab = 0"
      >
        FullStack
      </button>
      <button
        class="border p-5 font-bold transition-colors duration-100"
        :class="selectedTab === 1 ? 'bg-green-500' : null"
        @click="selectedTab = 1"
      >
        Mobile
      </button>
      <button
        class="border rounded rounded-l-none p-5 font-bold transition-colors duration-100"
        :class="selectedTab === 2 ? 'bg-green-500' : null"
        @click="selectedTab = 2"
      >
        Personal Qualities
      </button>
    </div>
    <transition name="fade" mode="out-in">
      <Fullstack v-if="selectedTab === 0" />
      <Mobile v-else-if="selectedTab === 1" />
      <Personal v-else-if="selectedTab === 2" />
    </transition>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class Skills extends Vue {
  selectedTab: number = 0
}
</script>

<style>
</style>
