<script lang="ts" setup>
import FirstComponentVue from "../components/FirstComponent.vue";

</script>
<template>
  <div class="about">

    <FirstComponent />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
