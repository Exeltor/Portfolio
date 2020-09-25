<template>
  <div class="grid lg:grid-cols-2 sm:grid-cols-1 gap-3">
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
          <img src="@/assets/vue-logo.png" alt="Vue" class="w-32 lg:mr-3">
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
      <h2 class="text-3xl font-bold leading-tight text-center mb-5">
        Backend
      </h2>
      <FlexContainer>
        <template #feature-content>
          <img src="@/assets/node-logo.svg" alt="node" class="w-32 lg:mr-3">
        </template>
        <template #content>
          <h3 class="text-3xl font-bold leading-tight">
            Node
          </h3>
          <small>Experience: 3 years</small>
          <p>
            Web servers including Express, JWT, Feathers.js, REST API's
          </p>
        </template>
      </FlexContainer>
      <FlexContainer>
        <template #feature-content>
          <img src="@/assets/firebase-logo.png" alt="Firebase" class="w-32 lg:mr-3">
        </template>
        <template #content>
          <h3 class="text-3xl font-bold leading-tight">
            Firebase
          </h3>
          <small>Experience: 3 years</small>
          <p>
            Backend as a Service of choice
            <br>
            I use it for many personal and professional projects. Fast setup and availability
          </p>
        </template>
      </FlexContainer>
      <FlexContainer>
        <template #feature-content>
          <img src="@/assets/graphql-logo.svg" alt="GraphQL" class="w-32 lg:mr-3">
        </template>
        <template #content>
          <h3 class="text-3xl font-bold leading-tight">
            GraphQL
          </h3>
          <small>Experience: 1 year</small>
          <p>
            This query language deserves more usage and recognition
            <br>
            The flexibility it offers makes it the best query language on the block!
          </p>
          <small>Everything has its ups and downs... REST is also great</small>
        </template>
      </FlexContainer>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class Fullstack extends Vue {}
</script>

<style>
</style>
