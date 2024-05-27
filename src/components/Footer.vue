<template>
    <q-footer class="bg-primary text-white q-pa-xs">
      <div class="row items-center justify-between q-mb-xs no-wrap">
        <div class="col-auto">
          <q-avatar square size="32px">
            <img src="https://i.pinimg.com/236x/e6/23/c5/e623c5231c596cfe4268d752fb8e10e3.jpg" alt="Logo">
          </q-avatar>
        </div>
        <div class="col q-pa-xs text-center">
          <div class="text-caption">Fauzi watch store, Jl. Pasir Putih, Pekanbaru</div>
          <div class="text-caption">Email: @Fauzi_watch_store | Telepon: 0812-3456-7890</div>
        </div>
        <div class="col-auto">
          <q-btn flat round dense icon="facebook" @click="goTo('https://facebook.com')" class="text-white">
            <q-tooltip content-class="bg-primary text-white">Facebook</q-tooltip>
          </q-btn>
          <q-btn flat round dense icon="twitter" @click="goTo('https://twitter.com')" class="text-white">
            <q-tooltip content-class="bg-primary text-white">Twitter</q-tooltip>
          </q-btn>
          <q-btn flat round dense icon="instagram" @click="goTo('https://instagram.com')" class="text-white">
            <q-tooltip content-class="bg-primary text-white">Instagram</q-tooltip>
          </q-btn>
        </div>
      </div>
      <div class="text-center q-pt-xs">
        &copy; 2024 Toko Online Saya
      </div>
    </q-footer>
  </template>
  
  <script>
  export default {
    name: 'Footer',
    methods: {
      goTo(url) {
        window.open(url, '_blank')
      }
    }
  }
  </script>
  
  <style scoped>
  .q-footer {
    border-top: 1px solid rgba(255, 255, 255, 0.2);
  }
  .row {
    display: flex;
    flex-wrap: nowrap;
    align-items: center;
  }
  .col-auto {
    flex: 0 0 auto;
  }
  .col {
    flex: 1;
    min-width: 0;
  }
  .q-pa-xs {
    padding: 4px;
  }
  .q-mb-xs {
    margin-bottom: 4px;
  }
  .q-pt-xs {
    padding-top: 4px;
  }
  .text-caption {
    font-size: 10px;
  }
  .q-avatar {
    width: 32px;
    height: 32px;
  }
  </style>
  