<template>
  <div class="social-networks">
      <SocialLink name="GitHub" to="https://github.com" icon="github.svg"/>
      <SocialLink name="Facebook" to="https://www.facebook.com" icon="facebook.svg"/>
      <SocialLink name="Twitter" to="https://www.twitter.com" icon="twitter.svg"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import {SocialLink} from '@/components/atoms'

export default defineComponent({
    components:{SocialLink}
})
</script>

<style lang="scss" scoped>
.social-networks{
    display: grid;
    grid-gap: 1rem;
}

</style>
