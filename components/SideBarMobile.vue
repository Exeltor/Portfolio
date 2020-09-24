<template>
  <div class="h-screen flex flex-row" :class="!isHidden ? 'w-screen' : 'w-16'">
    <div class="w-16 h-full flex flex-col justify-between bg-gray-800">
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
    <div v-if="!isHidden" class="h-full flex-grow" @click="$emit('hidesidebar')" />
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component({})
export default class SideBarMobile extends Vue {
  @Prop({ type: Boolean, required: true }) isHidden!: boolean
}
</script>

<style lang="postcss">
</style>
