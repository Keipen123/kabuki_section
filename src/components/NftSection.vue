<template>
  <LightBackground class="py-20 sm:py-40">
    <SectionTitle class="pb-8 sm:pb-16">
      <template v-slot:default>
        <span>NFT市場の</span>
      </template>
      <template v-slot:red>
        <span>可能性</span>
      </template>
    </SectionTitle>

    <NftContents />


  </LightBackground>
</template>

<script>
import LightBackground from '@/components/UI/LightBackground'
import SectionTitle from '@/components/UI/SectionTitle'
import NftContents from '@/components/NftContents'

export default {
  components: {
    LightBackground,
    SectionTitle,
    NftContents
  }
}
</script>