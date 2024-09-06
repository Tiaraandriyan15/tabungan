<template>
  <ul class="nav flex-column" style="background-color: blue;">
    <img src="" alt="">
    <li class="nav-item">
      <NuxtLink class="nav-link" href="siswa"><button class="btn btn-secondary">Siswa</button></NuxtLink>
    </li>
    <li class="nav-item">
      <NuxtLink class="nav-link" href="nabung"><button class="btn btn-secondary">Tabungan</button></NuxtLink>
    </li>
    <li class="nav-item">
      <NuxtLink class="nav-link" href="pengeluaran"><button class="btn btn-secondary">Pengeluaran</button></NuxtLink>
    </li>
    
</ul>
</template>

<style scope>
  .nav{
    min-height: 100vh;
    width: 180px;
  }
  .btn{
    width: 150px;
  }
</style>