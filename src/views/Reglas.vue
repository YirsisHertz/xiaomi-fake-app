<template>
  <div class="container border my-4 py-3 text-center">
    <h1>Reglas</h1>
    <hr />
    <div class="row">
      <div class="col-12 col-lg-8">
        <rules />
      </div>
      <div class="col-12 col-lg-4">
        <card />
      </div>
    </div>
  </div>
</template>

<script>
import Card from "../components/Card.vue";
import Rules from "../components/Rules.vue";
export default {
  components: { Card, Rules },
};
</script>
