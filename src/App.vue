<template>
  <div id="app">
    <Profile msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Profile from './views/Profile.vue'

export default {
  name: 'app',
  components: {
    Profile
  }
}
</script>

