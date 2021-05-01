<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, numquam alias! Quibusdam corporis voluptatum labore consectetur hic adipisci esse vero atque doloribus repudiandae. Possimus eaque necessitatibus dolor quibusdam accusamus illo."
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, numquam alias! Quibusdam corporis voluptatum labore consectetur hic adipisci esse vero atque doloribus repudiandae. Possimus eaque necessitatibus dolor quibusdam accusamus illo."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, numquam alias! Quibusdam corporis voluptatum labore consectetur hic adipisci esse vero atque doloribus repudiandae. Possimus eaque necessitatibus dolor quibusdam accusamus illo."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
