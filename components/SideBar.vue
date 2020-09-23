<template>
  <div class="w-16 flex flex-col justify-between bg-gray-800">
    <div></div>
    <div>
      <nuxt-link to="/">
        <div class="p-5">
          <PersonIcon />
        </div>
      </nuxt-link>
      <nuxt-link to="/work">
        <div class="p-5">
          <ComputerIcon />
        </div>
      </nuxt-link>
      <nuxt-link to="/skills">
        <div class="p-5">
          <CogIcon />
        </div>
      </nuxt-link>
    </div>
    <div>
      <a href="https://www.linkedin.com/in/exeltor/" target="_blank">
        <div class="p-5">
          <LinkedinIcon />
        </div>
      </a>
      <a href="https://github.com/Exeltor" target="_blank">
        <div class="p-5">
          <GithubIcon />
        </div>
      </a>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class MyClass extends Vue {}
</script>

<style lang="postcss">
</style>
