<template>
  <!-- component -->
  <!-- This is an example component -->
  <div v-if="loading">
    <div
      class="fixed top-0 left-0 z-50 w-screen h-screen flex items-center justify-center bg-white"
    >
      <div class="py-2 px-5 flex items-center flex-col">
        <div
          class="loader ease-linear rounded-full border-8 border-t-8 border-gray-200 h-24 w-24"
        ></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    loading: false
  }),
  methods: {
    start() {
      this.loading = true;
    },
    finish() {
      this.loading = false;
    }
  }
};
</script>

<style scoped>
.loader {
  border-top-color: #22c0ec;
  -webkit-animation: spinner 0.5s linear infinite;
  animation: spinner 0.5s linear infinite;
}

@-webkit-keyframes spinner {
  0% {
    -webkit-transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(360deg);
  }
}

@keyframes spinner {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
