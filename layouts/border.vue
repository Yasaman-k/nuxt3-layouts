<template>
  <div class="border-content">
    <slot />
  </div>
</template>

<style scoped>
  .border-content {
    padding: 0.5rem;
    border: 2px solid gray;
  }
</style>