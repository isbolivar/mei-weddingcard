<template>
<q-page>
<card-component></card-component>
</q-page>
</template>

<script>
import { defineComponent } from 'vue';
import CardComponent from 'components/CardComponent.vue'

export default defineComponent({
  name: 'PageIndex',
   components: { CardComponent }
})
</script>
