<template>
  <!-- BLOCOS PRINCIPAL -->
  <vs-col type="flex" vs-justify="center" vs-align="center" vs-sm="12" vs-xs="12" vs-lg="4">
    <vs-card>
      <!-- DESCRICAO DO BLOCO PRINCIPAL -->
      <div slot="header">
        <h5 class="descricao_card_conciliacao_bancaria">
          <b>Conciliação Bancária</b>
        </h5>
        <!--<p class="texto_centralizado_normal">Títulos</p> -->
      </div>

      <!-- BLOCOS DENTRO DO BLOCO PRINCIPAL -->
      <div>
        <vs-row vs-justify="center" class="baixo_do_card">
          <!-- BLOCO 01 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <h1 class="texto_centralizado_normal"> 198 </h1>
                <p class="texto_centralizado_descricao">Pendências totais</p>
              </div>
            </vs-card>
          </vs-col>

          <!-- BLOCO 02 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <h1 class="texto_centralizado_normal">12</h1>
                <p class="texto_centralizado_"> Notas em aberto </p>
              </div>
            </vs-card>
          </vs-col>

          <!-- BLOCO 03 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <h1 class="texto_centralizado_normal">12</h1>
                <p class="texto_centralizado_descricao">
                  Média de Conciliação
                </p>
              </div>
            </vs-card>
          </vs-col>

          <!-- BLOCO 04 -->
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
            <vs-card>
              <div slot="header">
                <h1 class="texto_centralizado_normal">4</h1>
                <p class="texto_centralizado_descricao">
                  Novas <br> notas
                </p>
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
  name: "CardConciliacaoBancaria",
  props: ["id", "titulo", "quantidade", "status"]
};
</script>

<style>
.descricao_card_conciliacao_bancaria {
  color: gray;
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
  margin-bottom: -17px
}
.desabilitado {
  background-color: #c3c3c3;
  color: gray;
}
</style>