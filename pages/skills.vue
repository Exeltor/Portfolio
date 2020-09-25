<template>
  <div class="min-h-full">
    <div class="h-screen/5 flex flex-col justify-center text-center">
      <h1 class="text-5xl font-bold text-green-400 leading-tight">
        My Skills
      </h1>
    </div>
    <div class="inline-block border rounded mx-auto">
      <button class="border-r">FullStack</button>
      <button class="border-r">Mobile</button>
      <button>Personal Qualities</button>
    </div>
    <div class="grid lg:grid-cols-2 sm:grid-cols-1">
      <div>
        <h2 class="text-3xl font-bold leading-tight text-center mb-5">
          Frontend
        </h2>
        <FlexContainer>
          <template #feature-content>
            <img src="@/assets/nuxt-logo.svg" alt="Nuxt" class="w-32 lg:mr-3">
          </template>
          <template #content>
            <h3 class="text-3xl font-bold leading-tight">
              Nuxt.js
            </h3>
            <small>Experience: 2 years</small>
            <p>
              A framework based on Vue to provide SSR capabilities and Static Site Generation
              <br>
              I use it extensively for many projects
            </p>
            <small>Psst... This portfolio is made and statically generated with Nuxt...</small>
          </template>
        </FlexContainer>
        <FlexContainer>
          <template #feature-content>
            <picture>
              <source srcSet="@/assets/vue-logo.png?webp" type="image/webp">
              <source srcSet="@/assets/vue-logo.png" type="image/png">
              <img src="@/assets/vue-logo.png" alt="Vue" class="w-32 lg:mr-3">
            </picture>
          </template>
          <template #content>
            <h3 class="text-3xl font-bold leading-tight">
              Vue
            </h3>
            <small>Experience: 2 years</small>
            <p>
              Learned it and quickly switched to Nuxt.js
            </p>
          </template>
        </FlexContainer>
        <FlexContainer>
          <template #feature-content>
            <img src="@/assets/angular-logo.svg" alt="Angular" class="w-32 lg:mr-3">
          </template>
          <template #content>
            <h3 class="text-3xl font-bold leading-tight">
              Angular
            </h3>
            <small>Experience: 3 years</small>
            <p>
              An all in one web framework from Google
              <br>
              This is the first framework I learned and I have developed multiple projects with it
            </p>
          </template>
        </FlexContainer>
      </div>
      <div>
        <h2 class="text-3xl font-bold leading-tight text-center">
          Backend
        </h2>
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
