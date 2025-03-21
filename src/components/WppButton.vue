<script setup>
import "bootstrap-icons/font/bootstrap-icons.css";
</script>
<template>
  <a
    href="https://wa.me/5531984666540"
    class="btn bg-success btn-animation position-fixed bottom-0 end-0 m-4 rounded-circle"
    target="_blank"
    aria-label="Entrar em contato no WhatsApp"
  >
    <i class="bi bi-whatsapp fs-5"></i>
  </a>
</template>

<style scoped>
.btn-animation {
  color: white;
  box-shadow: 0 4px 15px rgba(30, 0, 36, 0.808);
  animation: moveButton 2s infinite ease-in-out;
}

@keyframes moveButton {
  0% {
    transform: translateX(0);
  }
  50% {
    transform: translateX(10px);
  }
  100% {
    transform: translateX(0);
  }
}
</style>
