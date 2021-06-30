<template>
  <div class="home">
    <Crud msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Crud from '@/components/Crud.vue'

export default {
  name: 'Home',
  components: {
    Crud
  }
}
</script>
