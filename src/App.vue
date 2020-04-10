<template>
  <div id="app" class="appStyles">
    <router-view />
  </div>
</template>

<script>


export default {
  name: 'app',

  data: function() {
    return {

    }
  },

  components: {
  }

}
</script>

<style>
  .welcome{
    max-width: 400px;
    margin-top: 100px;
  }
  .welcome h2 {
    font-size: 3em;
  }
  .welcome button {
    margin: 30px auto;
  }
  .navbar nav {
    padding: 0 20px;
  }
</style>
