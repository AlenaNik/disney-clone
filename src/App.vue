<template>
  <div id="app" class="flex bg-gray-900 text-white min-h-screen">
    <SideBar/>
    <div class="w-full">
      <transition name="page" mode="out-in">
        <router-view/>
      </transition>
    </div>
  </div>
</template>
<script>
  import SideBar from "./views/SideBar";
  export default {
    components: { SideBar }
  }
</script>

<style src="./css/main.css">

</style>
