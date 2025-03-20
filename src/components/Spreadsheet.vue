<script setup>
import Card from "./Card.vue";
</script>

<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-12 col-md-8">
        <Card>
          <template #default>
            <h3 class="text-center">Planilha de Custo Orçamentário</h3>
            <p>
              Esta planilha tem como objetivo fornecer uma estimativa dos custos
              de diferentes tamanhos de projetos, levando em consideração o
              tempo estimado de trabalho e o custo total do escopo fechado. A
              tabela a seguir apresenta as faixas de horas estimadas e os custos
              associados para cada categoria de tamanho de projeto.
            </p>
            <table class="table table-bordered table-dark table-hover">
              <thead>
                <tr class="text-center align-middle">
                  <th scope="col">Tamanho</th>
                  <th scope="col">Horas Estimadas</th>
                  <th scope="col">Custo Total (Escopo Fechado)</th>
                </tr>
              </thead>
              <tbody>
                <tr class="text-center align-middle">
                  <td>P (Pequeno)</td>
                  <td>4 a 12 horas</td>
                  <td>R$ 160,00 a R$ 320,00</td>
                </tr>
                <tr class="text-center align-middle">
                  <td>M (Médio)</td>
                  <td>16 a 24 horas</td>
                  <td>R$ 480,00 a R$ 800,00</td>
                </tr>
                <tr class="text-center align-middle">
                  <td>G (Grande)</td>
                  <td>36 a 48 horas</td>
                  <td>R$ 1.120,00 a R$ 1.600,00</td>
                </tr>
                <tr class="text-center align-middle">
                  <td>GG (Muito Grande)</td>
                  <td>80 a 100 horas</td>
                  <td>R$ 2.400,00 a R$ 3.200,00</td>
                </tr>
              </tbody>
            </table>
            <div class="mt-3">
              <h5 class="text-purple">Observações:</h5>
              <ul>
                <li>
                  <strong>Variação de Preço:</strong> Os preços apresentados
                  podem sofrer variações dependendo do cenário de teste, como a
                  complexidade do projeto, ou até mesmo a necessidade de
                  revisões adicionais. Em alguns casos, o escopo pode ser
                  ajustado conforme as condições do projeto.
                </li>
                <li>
                  <strong>Descontos e Acréscimos:</strong> Em situações onde há
                  prazos apertados, a urgência pode acarretar em custos
                  adicionais. Por outro lado, projetos com maior prazo de
                  entrega podem permitir ajustes nos preços, oferecendo
                  descontos.
                </li>
                <li>
                  <strong>Condicionalidades:</strong> Certifique-se de que o
                  escopo do projeto esteja bem definido antes de iniciar, pois
                  mudanças frequentes no escopo podem resultar em acréscimos no
                  custo final.
                </li>
              </ul>
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

.table-bordered {
  border: 2px solid #b812ff;
}
</style>
