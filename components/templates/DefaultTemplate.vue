<template>
  <div>
    <slot />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'

@Component
export default class DefaultTemplate extends Vue {}
</script>

<style lang="scss" scoped></style>
