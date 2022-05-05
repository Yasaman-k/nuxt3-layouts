<template>
  <div class="container-fluid" style="max-width: 1200px;">
    <div class="row">
      <div class="col-12 col-md-6 bg-light py-3 border border-secondary">
        <slot name="list" />
      </div>
      <div class="col-12 col-md-6">
        <slot name="content" />
      </div>
    </div>
  </div>
</template>