<template>
  <vs-col type="flex" vs-justify="center" vs-align="center" vs-sm="12" vs-xs="12" vs-lg="4">
    <vs-card class="card-principal">
      <div slot="header">
        <h3> Suas atividades no sistema</h3>
      </div>
      <div>
        <ul class="activity-timeline">
          <li>
            <div class="timeline-icon bg-warning">
              <span class="feather-icon select-none relative">
                <vs-icon icon="warning" class="cor_do_icone"></vs-icon>
              </span>
            </div>
            <div class="timeline-info">
              <p class="font-semibold">Email Newsletter</p>
              <span class="activity-desc">Cupcake gummi bears soufflé caramels candy</span>
            </div>
            <small class="text-grey activity-e-time">15 days ago</small>
          </li>
          <li>
            <div class="timeline-icon bg-success">
              <span class="feather-icon select-none relative">
                <vs-icon icon="check_circle" class="cor_do_icone"></vs-icon>
              </span>
            </div>
            <div class="timeline-info">
              <p class="font-semibold">Email Newsletter</p>
              <span class="activity-desc">Cupcake gummi bears soufflé caramels candy</span>
            </div>
            <small class="text-grey activity-e-time">15 days ago</small>
          </li>
          <li>
            <div class="timeline-icon bg-primary">
              <span class="feather-icon select-none relative">
                <vs-icon icon="error_outline" class="cor_do_icone"></vs-icon>
              </span>
            </div>
            <div class="timeline-info">
              <p class="font-semibold">Email Newsletter</p>
              <span class="activity-desc">Cupcake gummi bears soufflé caramels candy</span>
            </div>
            <small class="text-grey activity-e-time">15 days ago</small>
          </li>
        </ul>
      </div>
    </vs-card>
  </vs-col>
</template>

<script>
export default {
  name: "CardTimeline"
};
</script>

<style>
    .cor_do_icone {
        color: #fff;
        font-size: 1.2rem;
    }
</style>