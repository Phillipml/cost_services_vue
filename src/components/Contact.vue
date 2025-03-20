<script setup>
import Card from "./Card.vue";
</script>

<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-12 col-sm-10 col-md-8 col-lg-6">
        <Card>
          <template #default>
            <div class="card-content">
              <img
                src="https://avatars.githubusercontent.com/u/105672582?v=4"
                alt="Phillip"
                class="img-fluid rounded-circle mb-3"
                width="150"
                height="150"
              />
              <h2 class="card-title">Dados de Contato</h2>
              <p>
                <strong class="text-purple">Email:</strong>
              </p>
              <p>contato.phillip.menezes@gmail.com</p>
              <p>
                <strong class="text-purple">Telefone:</strong>
              </p>
              <p>(31) 98466-6540</p>
            </div>
          </template>
        </Card>
      </div>
    </div>
  </div>
</template>

<style scoped>
.text-purple {
  color: #8e44ad;
}
.card {
  padding: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.card-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.card img {
  margin-bottom: 15px;
}
</style>
