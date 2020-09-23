<template>
  <div class="h-full grid grid-cols-2">
    <div class="m-auto">
      <h3 class="pt-3 text-xl leading-tight">
        Hey! My name is
      </h3>
      <h1 class="text-5xl font-bold text-green-400 leading-tight">
        Alexey Zhelezov
      </h1>
      <p>Full-stack developer and Big Data enthusiast</p>
      <p class="text-3xl mt-10">I will <span class="line-through text-gray-300">try to</span> solve your problems</p>
    </div>
    <div class="flex flex-col"></div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class MyClass extends Vue {

}
</script>

<style>
</style>
