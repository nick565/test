
<template>
  <div class="home">
    {{ name }}
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  data () {
    return {
      name: 'feferfef'
    }
  },
  components: {
    HelloWorld
  }
}
</script>
