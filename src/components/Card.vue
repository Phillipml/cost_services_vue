<template>
  <div class="card bg-dark text-white">
    <div class="card-body border-rounded">
      <slot></slot>
    </div>
  </div>
</template>

<style scoped>
.card {
  box-shadow: 0px 4px 16px rgba(170, 15, 184, 0.5);
  background: rgb(33, 10, 98);
  background: linear-gradient(
    345deg,
    rgba(33, 10, 98, 1) 0%,
    rgba(17, 3, 52, 1) 0%,
    rgba(11, 1, 37, 1) 20%,
    rgba(10, 1, 35, 1) 66%,
    rgba(9, 1, 32, 1) 99%
  );
}
</style>
