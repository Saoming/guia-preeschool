<template>
  <!-- test practice -->
  <div class="flex justify-between max-w-screen-2xl mx-auto pt-8 pb-12 border-b border-black">
    <!--  -->
    <div class=" flex items-center">
      <ul class="flex">
        <NuxtLink to="/guia">
          <li class="font-sans font-bold text-label text-midnightBlue pr-4"> Guía</li>
        </NuxtLink>
      </ul>
    </div>

    <!-- Logo -->
    <div class="">
      <NuxtLink to="/"><Logo /> </NuxtLink>
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
</template>


<script>
  export default {
    mounted() {
      feather.replace();
    }
  }

</script>
