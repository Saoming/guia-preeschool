<template>
  <footer class="max-w-screen-2xl">
    <section class="py-12 md:py-24 flex flex-wrap justify-between mx-auto">
      <div class="w-4/12">
        <h4 class="text-4xl font-bold mb-4">Enlaces</h4>
        <ul>
          <NuxtLink to="/guia">
            <li class="text-2xl font-light"> Guía</li>
          </NuxtLink>
          <li class="text-2xl font-light"><a href="mailto:parents.cal@ipefh.edu.mx"> parents.cal@ipefh.edu.mx </a> </li>
          <li class="text-2xl font-light"><a href="mailto:guiapreesco@ipefh.edu.mx"> guiapreesco@ipefh.edu.mx </a> </li>
        </ul>
      </div>
      <div class="w-4/12">
        <h4 class="text-4xl font-bold mb-4">Dirección</h4>
        <div class="text-xl">
          <span> Av. Calimaya, 52200 San Andrés Ocotlán, Méx. </span>
          <br /> <br />
          <span> Teléfono: 722 980 1831 </span>
        </div>
      </div>
      <div class="w-4/12">
        <h4 class="text-4xl font-bold mb-4">Redes Sociales</h4>
        <div class="flex justify-start">
          <button onclick="window.location.href='https://www.facebook.com/Guiapreesco'"
            class="focus:ring-4 focus:outline-non mr-6 mt-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-skyBlue hover:bg-skyBlue">
            <i data-feather="facebook"></i>
          </button>

          <button onclick="window.location.href='https://www.facebook.com/IPEFHCalimaya'"
            class="focus:ring-4 focus:outline-non mr-6 mt-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-skyBlue hover:bg-skyBlue">
            <i data-feather="facebook"></i>
          </button>

          <button onclick="window.location.href='https://www.instagram.com/guiapreesco/'"
            class="focus:ring-4 focus:outline-non mr-6 mt-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-skyBlue hover:bg-skyBlue">
            <i data-feather="instagram"></i>
          </button>

          <button onclick="window.location.href='https://www.instagram.com/ipefh_calimaya/'"
            class="focus:ring-4 focus:outline-non mr-6 mt-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-skyBlue hover:bg-skyBlue">
            <i data-feather="instagram"></i>
          </button>
        </div>
      </div>

    </section>
    <!-- footer -->
    <div class="flex justify-between mx-auto pt-12 pb-8 border-t border-black">
      <!--  -->
      <div class=" flex items-center">
        <ul class="flex">
          <li class="font-sans font-bold text-label text-midnightBlue pr-4"> © 2021 Guía Preesco. </li>
        </ul>
      </div>

      <!-- Logo -->
      <div class="">
        <Logo />
      </div>

      <!-- Buttons -->

      <div class="flex items-center">
        <div>
          <button
            onclick="window.location.href='https://sites.google.com/ipefh.edu.mx/guiapreescoipefh/formularios?authuser=0'"
            class="focus:ring-4 focus:outline-non mt-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-skyBlue hover:bg-skyBlue">
            Inscribirse &nbsp; <i data-feather="chevrons-right"></i>
          </button>
          
          <NuxtLink to="/faq"> 
          <button
            class="focus:ring-4 focus:outline-non mt-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-sandyBrown hover:bg-sandyBrown">
            FAQ &nbsp; <i data-feather="copy"></i>
          </button>
          </NuxtLink>
        </div>
      </div>
      <!--  -->
    </div>
  </footer>
</template>


<script>
  export default {
    mounted() {
      // feather icons
      feather.replace();
    }
  }

</script>

<style>

</style>
