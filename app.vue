<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<style scoped>
.page-enter-action{
  transition: all 0.2s;
}
.page-enter-from,
.page-leave-to{
  filter: grayscale(1);
}
</style>
