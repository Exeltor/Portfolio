<template>
  <div class="h-12 shadow sticky top-0 flex flex-row justify-between bg-gray-800">
    <button class="w-12 p-3" @click="$emit('sidebar')">
      <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
      </svg>
    </button>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class MyClass extends Vue {}
</script>

<style lang="postcss">
</style>
