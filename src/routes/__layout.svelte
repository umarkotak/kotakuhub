<script>
  import Navbar from "../components/Navbar.svelte"
  import Sidebar from "../components/Sidebar.svelte"
</script>

<div class="sidebar-mini layout-fixed layout-navbar-fixed dark-mode text-sm" data-new-gr-c-s-check-loaded="14.1038.0" data-gr-ext-installed="" style="height: auto;">
  <div class="wrapper">
    <Navbar />

    <Sidebar />

    <slot />
  </div>
</div>
