<template>
    <div class="q-pa-md">
      <h2 class="text-h5">Testimoni Pelanggan</h2>
      <div v-for="(testimonial, index) in testimonials" :key="index" class="testimonial">
        <q-avatar :size="40" :text-color="'white'" class="q-mr-sm">{{ testimonial.name.charAt(0) }}</q-avatar>
        <div>
          <div class="text-subtitle2">{{ testimonial.name }}</div>
          <p>{{ testimonial.comment }}</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        testimonials: [
          { name: "John Doe", comment: "Produk Berkualitas luar biasa! pasti akan belanja disana lagi." },
          { name: "Jane Smith", comment: "Pengiriman cepat dan layanan pelanggan yang sangat baik." },
          { name: "Alice Johnson", comment: "Suka dengan beragam pilihan pakaian yang tersedia." }
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  .testimonial {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
  }
  
  .text-subtitle2 {
    font-size: 0.875rem;
  }
  </style>
  