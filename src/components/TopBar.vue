<template>
  <div>
  <div class="ui borderless main large menu fixed">
    <!-- Browse button -->
    <a class="item">Reddit Spotify Playlists</a>
    <!-- search button -->
    <div class="ui category search item">
      <div class="ui transparent icon input">
        <input class="prompt" type="text" placeholder="Search...">
        <i class="search link icon"></i>
      </div>
    </div>
  </div>
  <div class="ui borderless main large menu placeholder" style="visibility:hidden;"></div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello topbar!'
    }
  }
}
</script>

<style scoped>

</style>
