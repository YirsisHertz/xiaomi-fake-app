<template>
  <div class="container text-center my-4 border py-3">
    <img alt="Vue logo" src="../assets/logo.png" />
    <h1>Xiaomi Poco F2 Pro</h1>
    <hr />
    <Table />
    <hr />
    <alert />
    <btn />
  </div>
</template>

<script>
import Alert from "./Alert.vue";
import Btn from "./Btn.vue";
import Table from "./Table.vue";
export default {
  components: { Table, Btn, Alert },
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
