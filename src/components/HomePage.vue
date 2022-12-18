<template>
  <div id="bg" class="min-vh-100 d-flex align-items-center text-center">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <h1 class="text-uppercase text-white fw-semibold display-1">Selamat Datang</h1>
          <h5 class="text-white mt-3 mb-4">SUPERMARKET UAS PAW KELAS A KELOMPOK H</h5>
          <div>
            <router-link :to="{ name: 'Login' }"><button type="button" class="btn btn-primary me-2">Login</button></router-link>
            <router-link :to="{ name: 'Register' }"><button type="button" class="text-white btn btn-success ms-2">Register</button></router-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
#bg {
  background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.5)), url(https://img.freepik.com/premium-vector/grocery-supermarket-interior-with-full-product-shelves_53562-8921.jpg?w=2000);
  background-position: center;
  background-size: cover;
}
</style>
