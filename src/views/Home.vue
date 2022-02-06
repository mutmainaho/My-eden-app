<template>
  <div class="home">
    <dog-list/>
  </div>
</template>

<script>
// @ is an alias to /src
import DogList from '@/components/DogList.vue'

export default {
  name: 'Home',
  components: {
    DogList
    
  }
}
</script>
