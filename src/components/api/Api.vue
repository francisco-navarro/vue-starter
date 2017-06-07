<template>
  <div class="hello">
    <h1>API Library</h1>
    {{library}}
    <ul>  
      <li><a href="#api">API Docs</a></li>
    </ul>
  </div>
</template>

<script>
import library from './api-library.service';

export default {
  data() {
    return {
      library,
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
