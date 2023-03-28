<template>
  <div id="app">
    <img alt="Vue logo" src="data:image/png;base64,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" />
    <HelloWorld msg="Welcome To SMK Telkom Makassar" />
    <tombol msg="" class="btn btn-danger" />
    <nama />
    <klik />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import tombol from './components/tombol.vue';
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap.js';
import nama from './components/nama.vue';
import klik from './components/klik.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    tombol,
    nama,
    klik,
  },
  data(){
    return {
      author: 'jogjaide'
    }
  },
  provide(){
    return {
      providedAuthor: this.author
    }
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
