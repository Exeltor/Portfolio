<template>
  <div class="flex flex-col items-center text-center lg:text-left lg:flex-row border-2 border-gray-800 rounded p-5 mb-5">
    <slot name="feature-content" />
    <div class="break-word">
      <slot name="content" />
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class FlexContainer extends Vue {}
</script>

<style lang="postcss">
</style>
