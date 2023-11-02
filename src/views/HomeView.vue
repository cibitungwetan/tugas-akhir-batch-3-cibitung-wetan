<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />
    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold my-4">Visi&Misi Desa Cibitung Wetan</p>
      <p class="text-lg font-semibold">Visi</p>
      <p> “Mewujudkan Masyarakat Desa Cibitung Wetan yang “ SERASI” (Sehat, Rapi, Aman dan Sejahtera) Pada Tahun 2029”
          <p class="text-lg font-semibold">Misi</p>
           <li>
          1.Mewujudkan pemerintah Desa Cibitung Wetan yang efektif dan efisien dalam rangka mengoptimalkan pelayanan kepada masyarakat;
        </li>
        <li>
          2.Meningkatkan derajat hidup masyarakat melalui upaya peningkatan pelayanan Kesehatan desa;
        </li>
        <li>
          3.Meningkatkan pembangunan infrastruktur yang mendukung perekonomian desa;
        </li>
        <li>
          4.Menjaga kelestarian dan sumber daya alam untuk memenuhi kebutuhan dan pemerataan guna meningkatkan perekonomian;
        </li>
        <li>
          5.Mewujudkan perekonomian yang memiliki daya saing dan berkelanjutan;
        </li>
       
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
