<template>
  <div class="home">
    <div class="main">
      <HellowWrold/>
    </div>
    <div class="footer">
     <router-link>dddd</router-link>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HellowWrold from '../components/HelloWorld'
export default {
  name: 'home',
  components: {
    HellowWrold
  }
}
</script>
