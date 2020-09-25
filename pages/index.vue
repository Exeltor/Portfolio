<template>
  <div class="min-h-full grid lg:grid-cols-2 sm:grid-cols-1">
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
    <div class="flex flex-col justify-center">
      <FlexContainer>
        <template #feature-content>
          <img src="@/assets/mubint-logo.svg" alt="Mubint" class="w-32 lg:mr-3">
        </template>
        <template #content>
          <h3 class="text-3xl font-bold leading-tight">
            International Academy of Business and New Technologies
          </h3>
          <small>Jul 2016 - Aug 2016</small>
          <p>
            System Administrator Internship
          </p>
        </template>
      </FlexContainer>
      <FlexContainer>
        <template #feature-content>
          <img src="@/assets/valorantify-logo.png" alt="Valorantify" class="w-32 lg:mr-3">
        </template>
        <template #content>
          <h3 class="text-3xl font-bold leading-tight">
            Valorantify
          </h3>
          <small>Jun 2020 - Aug 2020</small>
          <p>
            Lead Developer
            <br>
            Platform to view statistics and news related to professional Valorant
          </p>
        </template>
      </FlexContainer>
      <FlexContainer>
        <template #feature-content>
          <img src="@/assets/flintgg-logo.png" alt="Flint.gg" class="w-32 lg:mr-3">
        </template>
        <template #content>
          <h3 class="text-3xl font-bold leading-tight">
            Flint.gg
          </h3>
          <small>Aug 2020</small>
          <p>
            FrontEnd Developer - Freelance
            <br>
            Implementation of sharing feature for social networks, backend canvas drawing and use of native share mobile API
          </p>
        </template>
      </FlexContainer>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class Index extends Vue {

}
</script>

<style>
</style>
