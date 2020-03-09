<template>
  <!-- BLOCOS PRINCIPAL -->
   <vs-col type="flex" vs-justify="center" vs-align="center" vs-sm="12" vs-xs="12" vs-lg="4">
    <vs-card>
      <div slot="header">
        <h5 class="descricao_card">
          <b>Consolidação de Baixas</b>
        </h5>
      </div>

      <div>
        <vs-row vs-justify="center" class="baixo_do_card">
          <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="12" class="card">
            <vs-card>
              <div slot="header">
                <h1 class="texto_centralizado_divergente">14</h1>
                <p class="texto_centralizado_divergente">Notas en aberto</p>
              </div>
            </vs-card>
          </vs-col>
          <vs-row vs-justify="center" class="baixo_do_card">
            <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
              <vs-card>
                <div slot="header">
                  <h1 class="texto_centralizado_normal">12</h1>
                  <p class="texto_centralizado_normal">Situações em aberto</p>
                </div>
              </vs-card>
            </vs-col>
            <vs-col type="flex" vs-justify="center" vs-align="center" vs-w="6" class="card">
              <vs-card>
                <div slot="header">
                  <h1 class="texto_centralizado_normal">14 m</h1>
                  <p class="texto_centralizado_normal">Média de resolução</p>
                </div>
              </vs-card>
            </vs-col>
          </vs-row>
        </vs-row>
      </div>
    </vs-card>
  </vs-col>
</template>

<script>
    export default {
        name: "CardConsolidacaoBaixas",
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
    margin-bottom: -8px;
  }
</style>
