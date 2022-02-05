<template>
  <div class="bg-slate-50 h-screen flex flex-col">
    <header-vue></header-vue>
    <router-view></router-view>
  </div>
</template>

<script>
import HeaderVue from "./components/Header.vue";

export default {
  components: {
    HeaderVue,
  },
};
</script>
