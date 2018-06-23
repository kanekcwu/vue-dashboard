<template>
  <footer class="footer">
    <div class="container-fluid d-flex flex-wrap justify-content-between">
      <nav>
        <ul>
          <li>
            <router-link :to="{path:'/dashboard'}">Dashboard</router-link>
          </li>
          <li>
            <router-link :to="{path:'/maps'}">Map</router-link>
          </li>
          <li>
            <router-link :to="{path:'/notifications'}">Notifications</router-link>
          </li>
        </ul>
      </nav>
      <div class="copyright d-flex flex-wrap">
        &copy; Made with
        <i class="fa fa-heart heart"></i> by
        <a href="https://github.com/HackTheRack2018-ObsidianAdvisoryLLP/vue-dashboard/" target="_blank"> &nbsp; Obsidian Advisory LLP</a>
      </div>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style>
</style>
