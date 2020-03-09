<template>
  <!-- BLOCOS PRINCIPAL -->
  <vs-col type="flex" vs-justify="center" vs-align="center" vs-sm="12" vs-xs="12" vs-lg="4">
    <vs-card>
      <!-- DESCRICAO DO BLOCO PRINCIPAL -->
      <div slot="header">
        <h5 class="descricao_card">
          <b>Consolidação de Movimentos</b>
        </h5>
        <p class="texto_centralizado_normal">Títulos</p>
      </div>

      <!-- BLOCOS DENTRO DO BLOCO PRINCIPAL -->
      <div>
        <vs-row vs-justify="center" class="baixo_do_card">
          <!-- BLOCO 01 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <p class="texto_centralizado_divergente">Divergentes</p>
                <h1 class="texto_centralizado_divergente">14</h1>
              </div>
            </vs-card>
          </vs-col>

          <!-- BLOCO 02 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <p class="texto_centralizado_normal">A Pagar</p>
                <h1 class="texto_centralizado_normal">12</h1>
              </div>
            </vs-card>
          </vs-col>

          <!-- BLOCO 03 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <p class="texto_centralizado_normal">
                  Totais
                </p>
                <h1 class="texto_centralizado_normal">12</h1>
              </div>
            </vs-card>
          </vs-col>

          <!-- BLOCO 04 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <p class="texto_centralizado_normal">
                  A Receber
                </p>
                <h1 class="texto_centralizado_normal">4</h1>
              </div>
            </vs-card>
          </vs-col>

        </vs-row>
      </div>
    </vs-card>
  </vs-col>
</template>

<script>
export default {
  name: "CardConsolidacaoMovimentos",
  props: ["id", "titulo", "quantidade", "status"]
};
</script>

<style>
.descricao_card {
  color: #008cd6;
  text-align: center;
}
.texto_centralizado_normal {
  text-align: center;
  font-weight: bold;
}
.texto_centralizado_divergente {
  color: #f04732;
  font-weight: bold;
  text-align: center;
}
.texto_centralizado_atencao {
  color: #f0e432;
  font-weight: bold;
  text-align: center;
}
.texto_centralizado_descricao {
  text-align: center;
}
.card {
  padding: 10px;
  margin: -14px;
  height: 95%;
}
.baixo_do_card {
  margin-bottom: -10px
}
</style>