<template>
  <NuxtLayout name="sidebar">
    <template #list>
      <!--List content-->
      <ol>
        <li>Topic 1</li>
        <li>Topic 2
          <ol type="a">
            <li>Subtopic 2.1</li>
            <li>Subtopic 2.2</li>
          </ol>
        </li>
        <li>Topic 3</li>
      </ol>
    </template>
    <template #content>
      This is the main content of <span>pages/index.vue</span> with the custom side bar.
    </template>
  </NuxtLayout>
</template>

<style scoped>
span {
  font-family: monospace;
}
</style>