<template>
  <div>
   <hero-v />
   <item-v />
   <equipment-v />
   <slide-v />
  </div>
</template>

<script>
import EquipmentV from '@/components/EquipmentV.vue'
import HeroV from '@/components/HeroV.vue'
import ItemV from '@/components/ItemV.vue'
import SlideV from '@/components/SlideV.vue'
export default {
  name: 'HomeView',
  components: {
    HeroV,
    ItemV,
    SlideV,
    EquipmentV
  }
}
</script>
