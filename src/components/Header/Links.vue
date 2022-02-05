<template>
  <div class="flex items-center h-full relative w-full max-w-sm">
    <a @click="active = 'Grades'"
      :class="{ 'text-sky-500 hover:text-sky-500': active == 'Grades' }"
      href="#"
      class="w-1/3 flex justify-center text-sm font-semibold text-gray-400 hover:text-gray-800 transition duration-400"
      >Grades</a
    >
    <a @click="active = 'Schedule'"
      href="#"
      :class="{ 'text-sky-500 hover:text-sky-500': active == 'Schedule' }"
      class="w-1/3 flex justify-center text-sm font-semibold text-gray-400 hover:text-gray-800 transition duration-400"
      >Schedule</a
    >
    <a @click="active = 'Comunnity'"
      href="#"
      :class="{ 'text-sky-500 hover:text-sky-500': active == 'Comunnity' }"
      class="w-1/3 flex justify-center text-sm font-semibold text-gray-400 hover:text-gray-800 transition duration-400"
      >Comunnity</a
    >
    <span
      ref="bar"
      class="w-1/3 bg-sky-500 absolute h-0.5 bottom-0 shadow shadow-sky-500/20 transform translate-y-0.5"
    ></span>
  </div>
</template>

<script>
import anime from "animejs/lib/anime.es.js";
export default {
  data() {
    return {
      active: "Comunnity",
      naValue: 0,
    };
  },
  methods: {
    activeBar() {
      anime({
        targets: this.$refs.bar,
        translateX: -this.naValue + "%",
        translateY: '0.125rem',
        left: this.naValue + "%",
        duration: 500,
        easing: "easeInOutElastic(1, .8)",
      });
    },
  },
  watch: {
    active(newValue) {
      this.naValue = newValue === "Grades" ? 0 : newValue === "Schedule" ? 50 : 100;
      this.activeBar();
    },
  },
};
</script>