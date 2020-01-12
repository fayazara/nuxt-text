<template>
  <div class="container bg-gray-600">
    <div>
      <logo />
      <h1 class="title">
        prahlad-tailwind
      </h1>
      <h2 class="subtitle">
        prahlads site with tailwind
      </h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

