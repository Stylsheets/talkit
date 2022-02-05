<template>
  <nav
    class="flex flex-shrink-0 justify-between w-full bg-white px-20 items-center h-20 border-b border-slate-50 shadow-md z-10"
  >
    <div class="w-full max-w-7xl mx-auto flex items-center justify-between h-full">
      <div class="flex h-full items-center space-x-4">
        <div class="pr-6 h-12 flex-shrink-0">
          <img src="../assets/logo.svg" class="h-full w-full" alt="logo" />
        </div>
        <HeaderSearch />
      </div>
      <HeaderLinks />
      <div class="">
          test
      </div>
    </div>
  </nav>
</template>

<script>
import HeaderSearch from "./Header/Search.vue";
import HeaderLinks from "./Header/Links.vue";
export default {
    components: {
        HeaderSearch,
        HeaderLinks
    },
};
</script>
