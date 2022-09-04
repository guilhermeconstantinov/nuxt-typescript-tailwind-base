<template>
  <div>teste: {{ user }}</div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'nuxt-property-decorator'

@Component
export default class Teste extends Vue {
  @Prop()
  user!: string
}
</script>

<style>
</style>