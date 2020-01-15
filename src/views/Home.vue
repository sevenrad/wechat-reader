<template>
  <div class="home">
    <span class="icon-bookmark"></span>
  </div>
</template>

<script>
// @ is an alias to /src
import Epub from 'epubjs'
global.epub = Epub
export default {
}
</script>

<style scoped>
  .icon-bookmark {
    font-size: 40px;
  }
</style>
