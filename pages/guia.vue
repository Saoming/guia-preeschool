<template>
  <div class="font-sans">
    <Header />
    <section class="w-full px-10">
      <div class="flex justify-between py-14">
        <div class="w-2/4 flex justify-center">
          <no-ssr>
            <vue-tiny-slider v-bind="tinySliderOptions">
              <div>
                <img src="~assets/happy-parents-img.png" alt="Placeholder"
                  class="" />
              </div>
              <div>
                <img src="~assets/happy-parents-img.png" alt="Placeholder"
                  class="" />
              </div>
                <div>
                <img src="~assets/happy-parents-img.png" alt="Placeholder"
                  class="" />
              </div>
                <div>
                <img src="~assets/happy-parents-img.png" alt="Placeholder"
                  class="" />
              </div>

            </vue-tiny-slider>
          </no-ssr>
        </div>

        <div class="w-2/4 px-14 flex flex-col justify-start items-start">
          <h2 class="text-midnightBlue text-heading font-bold mb-7"> E-Book Guía <span class="text-coral">
              Preesco</span> </h2>
          <p class="text-lg mb-12"> Hola, <br /> <br />
            Te invitamos a que descargues el Ebook en donde <br /> podrás conocer mas a detalle todos los beneficios
            <br /> y obtener un atractivo descuento.
          </p>
          <OptinForm />
        </div>
      </div>
    </section>
  </div>
</template>


<script>
  export default {
    head: {
      link: [{
        rel: "stylesheet",
        href: "https://cdnjs.cloudflare.com/ajax/libs/tiny-slider/2.9.1/tiny-slider.css",
      }],
      script: [{
          src: "https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js",
        },
        {
          src: "https://unpkg.com/feather-icons"
        }
      ]
    },
    data() {
      return {
        tinySliderOptions: {
          mouseDrag: true,
          loop: true,
          items: 1,
          swipeAngle: 45,
          controlsText: [
            '<svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="butt" stroke-linejoin="bevel" data-v-1c6aabbe=""><path d="M15 18l-6-6 6-6" data-v-1c6aabbe=""></path></svg>',
            '<svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="butt" stroke-linejoin="bevel" data-v-1c6aabbe=""><path d="M9 18l6-6-6-6" data-v-1c6aabbe=""></path></svg>',
          ],
        },
      }
    },
    mounted() {
      feather.replace();
    }
  }

</script>

<style>
  .tns-outer {
    position: relative;
  }

  .tns-controls {
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: 99;
    @apply absolute md:left-0 md:bottom-0 w-full hidden md:flex items-center justify-start mt-10 md:mt-0 py-0 md:py-8 px-0 md:px-12;
  }

  .tns-controls>button {
    @apply focus:ring-4 focus:outline-none inline-flex items-center justify-center p-2 border border-transparent rounded-lg shadow-sm text-base font-medium text-white bg-gray-800 hover:bg-gray-800 ml-6;
  }

  .tns-nav {
    display: none;
  }

</style>
