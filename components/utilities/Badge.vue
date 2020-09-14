<template>
  <div class="rounded-full bg-gray-800 h-6">
    <img class="h-full p-1" :src="imageFromPath" alt="Icon">
    <p class="p-0 uppercase">
      {{ text }}
    </p>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component({})
export default class MyClass extends Vue {
  @Prop({ type: String, required: true }) imagePath!: string
  @Prop({ type: String, required: true }) text!: string

  get imageFromPath () {
    return require('@/assets/checkmark.svg')
  }
}
</script>

<style>
</style>
