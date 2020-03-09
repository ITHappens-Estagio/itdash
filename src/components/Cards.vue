<template>
  <div>
    <vs-row vs-justify="center">
      <CardTimeline/>
      <CardConciliacaoBancaria/>
    </vs-row>

    <vs-row vs-justify="center">
      <CardConsolidacaoMovimentos/>
      <CardConsolidacaoEntradas/>
      <CardRCA/>
      <CardConsolidacaoVendas/>
      <CardConsolidacaoBaixas/>
      <CardFechamentoFolhaFerias/>
    </vs-row>
  </div>
</template>

<script>
import CardTimeline from '../components/CardTimeline'
import CardConciliacaoBancaria from '../components/CardConciliacaoBancaria'
import CardConsolidacaoMovimentos from '../components/CardConsolidacaoMovimentos'
import CardConsolidacaoEntradas from '../components/CardConsolidacaoEntradas'
import CardRCA from '../components/CardRCA'
import CardConsolidacaoVendas from '../components/CardConsolidacaoVendas'
import CardConsolidacaoBaixas from '../components/CardConsolidacaoBaixas'
import CardFechamentoFolhaFerias from '../components/CardFechamentoFolhaFerias'

export default {
  name: "Cards",
  components: {
    CardFechamentoFolhaFerias,
    CardConsolidacaoBaixas,
    CardConsolidacaoVendas,
    CardTimeline,
    CardConciliacaoBancaria,
    CardConsolidacaoMovimentos,
    CardConsolidacaoEntradas,
    CardRCA

  }
};
</script>

<style>
.card-principal {
  background-color: #9bd0ff1a;
  color: #000;
}
#tigrao {
  height: 93%;
}

</style>
