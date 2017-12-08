<template>
  <div>
    <div class="phone-viewport">
      <md-bottom-bar md-sync-route>
        <md-bottom-bar-item to="/components/bottom-bar/home" md-label="Home" md-icon="home"></md-bottom-bar-item>
        <md-bottom-bar-item to="/components/bottom-bar/posts" md-label="Pages" md-icon="pages"></md-bottom-bar-item>
        <md-bottom-bar-item to="/components/bottom-bar/favorites" md-label="Favorites" md-icon="favorite"></md-bottom-bar-item>
      </md-bottom-bar>
    </div>

  </div>
</template>

<script>
  export default {
    name: 'BarRouter'
  }
</script>

<style>
 body {
  max-width: 480px;
  margin: 0 auto;
 }
  .phone-viewport {
    text-align: center;
    width: 100%;
    height: 500px;
    display: inline-flex;
    align-items: flex-end;
    overflow: hidden;
    border: 1px solid rgba(#000, .26);
    background: rgba(#000, .06);
  }
</style>