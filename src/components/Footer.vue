<template>
  <footer class="bg-dark text-white w-100 p-4">
    <div class="row text-center">
      <div class="col-6">
        <p>Contacto</p>
        <hr />
        Twitter: <a href="#">@xiaomi_mx</a>
        <br />
        Instagram: <a href="#">@xiaomi_mx</a>
      </div>
      <div class="col-6">
        <p>Creditos</p>
        <hr />
        <p>&copy; Yirsis Serrano - {{ year }}</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  computed: {
    year() {
      return new Date().getFullYear();
    },
  },
};
</script>
