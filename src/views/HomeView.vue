<template>
  <div>
    <HelloWorld :light="true" buttonText="Click"/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  },
  
}
</script>

