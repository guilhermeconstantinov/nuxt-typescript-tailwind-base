<template>
  <div>
    <Teste user="teste" />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'
import Teste from '~/components/Teste.vue'

@Component({ components: { Teste } })
export default class PageIndex extends Vue {}
</script>
