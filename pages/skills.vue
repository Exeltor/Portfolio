<template>
  <div class="min-h-full">
    <div class="h-screen/5 flex flex-col justify-center text-center">
      <h1 class="text-5xl font-bold text-green-400 leading-tight">
        My Skills
      </h1>
    </div>
    <div class="grid lg:grid-cols-2 sm:grid-cols-1">
      <div>
        <h2 class="text-3xl font-bold leading-tight text-center">Frontend</h2>
      </div>
      <div>
        <h2 class="text-3xl font-bold leading-tight text-center">Backend</h2>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class MyClass extends Vue {}
</script>

<style>
</style>
