<template>
  <div class="home">
    <img style="max-width: 250px" alt="Vue logo" src="../assets/baiiva_logo.svg">
    <HelloWorld msg="Welcome to Baiiva App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>
