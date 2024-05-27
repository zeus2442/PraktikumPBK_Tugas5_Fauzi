<template>
    <q-header elevated class="bg-primary text-white">
      <q-toolbar>
        <q-btn
          flat
          round
          dense
          icon="menu"
          aria-label="Menu"
          @click="onMenuClick"
        />
  
        <q-toolbar-title>
          <q-avatar square>
            <img
              src="https://i.pinimg.com/236x/e6/23/c5/e623c5231c596cfe4268d752fb8e10e3.jpg"
              alt="Logo"
            />
          </q-avatar>
          <span class="q-ml-sm">FAUZI WATCH STORE</span>
        </q-toolbar-title>
  
        <q-btn flat round dense icon="home" aria-label="Home">
          <q-tooltip content-class="bg-primary text-white">Home</q-tooltip>
        </q-btn>
        <q-btn flat round dense icon="shopping_cart" aria-label="Produk">
          <q-tooltip content-class="bg-primary text-white">Produk</q-tooltip>
        </q-btn>
        <q-btn flat round dense icon="contacts" aria-label="Kontak">
          <q-tooltip content-class="bg-primary text-white">Kontak</q-tooltip>
        </q-btn>
  
        <q-space />
  
        <q-btn flat round dense icon="account_circle" aria-label="Akun">
          <q-tooltip content-class="bg-primary text-white">Akun</q-tooltip>
        </q-btn>
        <q-btn flat round dense icon="shopping_cart" aria-label="Keranjang">
          <q-tooltip content-class="bg-primary text-white">Keranjang</q-tooltip>
        </q-btn>
      </q-toolbar>
    </q-header>
  </template>
  
  <script>
  export default {
    name: "Navbar",
    methods: {
      onMenuClick() {
        // Handle menu click
      },
    },
  };
  </script>
  
  <style scoped>
  .q-toolbar-title {
    display: flex;
    align-items: center;
  }
  
  .q-toolbar-title img {
    height: 40px;
  }
  
  .q-btn {
    margin-left: 10px;
  }
  </style>
  