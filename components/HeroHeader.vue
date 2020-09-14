<template>
  <div class="h-screen/2 xl:px-56 shadow-md grid grid-cols-2">
    <div class="my-auto">
      <h3 class="pt-3 text-xl leading-tight">
        Hey! My name is
      </h3>
      <h1 class="text-5xl font-bold text-green-400 leading-tight">
        Alexey Zhelezov
      </h1>
      <p>Computer Engineering student in Madrid</p>
      <p class="text-3xl mt-3">I will <span class="line-through text-gray-300">try to</span> solve your problems</p>
    </div>
    <div class="flex flex-col">
      <img class="rounded object-cover h-64" src="@/assets/self-picture.jpg" alt="Alexey Zhelezov">
      <!-- <LinkedinIcon />
      <GithubIcon /> -->
      <Badge image-path="@/assets/checkmark.svg" text="Trial badge" />
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
