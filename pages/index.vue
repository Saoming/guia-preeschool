<template>
  <div class="font-sans">
    <!-- Header -->
    <Header />
    <!-- Body -->
    <main class="max-w-screen-2xl h-full mx-auto">
      <!-- 1st section -->
      <section class="w-full py-24 bg-pattern-1 mb-12">
        <div class="text-center pb-16">
          <h1 class="text-heading text-midnightBlue font-bold"> Este 2021 <span class="text-coral">Certifica </span>
          </h1>
          <h3 class="text-4xl text-midnightBlue font-bold"> El nivel preescolar de tus hijos <br /> desde la comodidad
            de tu casa! </h3>
        </div>
        <!--  -->
        <div class="flex flex-col justify-center">
          <p class="text-2xl text-black opacity-50 text-center mb-6"> Maternal, Kinder 1, 2 y 3. </p>
          <!--  -->
          <div class="max-w-3xl mx-auto">
            <div class="flex justify-center">
              <NuxtLink to="/guia">
              <button
                class="focus:ring-4 focus:outline-non mr-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-skyBlue hover:bg-skyBlue">
                Guía Preesco &nbsp; <i data-feather="book"></i>
              </button>
              </NuxtLink>

              <NuxtLink to="/faq">
              <button
                class="focus:ring-4 focus:outline-non mr-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-skyBlue hover:bg-skyBlue">
                Testimonios  &nbsp; <i data-feather="coffee"></i>
              </button>
             </NuxtLink>

            </div>
          </div>
        </div>
      </section>
      <!-- 2nd Sections -->
      <section class="w-full rounded-2xl bg-floralWhite mb-24" style="height: 604px;">
        <div class="py-12 flex justify-around">

          <div class="w-1/3 flex items-center px-12 border-r border-gray-300">
            <div>
              <h2 class="text-4xl text-coral font-bold mb-7"> ¿Qué te ofrecemos?</h2>
              <p class="text-2xl text-black opacity-50"> En IPEFH, nuestro compromiso es que <br /> cada uno de nuestros
                alumnos descubra, <br /> desarrolle y proyecte sus talentos. </p>
              <div class="flex mt-12">
                <button
                  onclick="window.location.href='https://sites.google.com/ipefh.edu.mx/guiapreescoipefh/formularios?authuser=0'"
                  class="focus:ring-4 focus:outline-non font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-coral hover:bg-coral">
                  Comienza Ahora &nbsp; <i data-feather="arrow-right"></i>
                </button>
                <button
                  class="focus:ring-4 focus:outline-non font-bold whitespace-nowrap inline-flex items-center justify-center px-3 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-white hover:bg-white">
                  <img src="~assets/play.svg" width="32px" height="32px" />
                </button>
              </div>
            </div>
          </div>

          <div class="w-1/2">
            <div class="flex justify-between">
              <div class="w-1/2">
                <img src="~assets/educacion-icon.png" />
                <h3 class="text-label text-midnightBlue font-bold mb-4"> Educacion Flexible </h3>
                <p class="text-lg"> Una modalidad educativa flexible que <br /> se adapte a las necesidades de cada
                  <br /> familia. </p>
              </div>

              <div class="w-1/2">
                <img src="~assets/desarrollo-icon.png" />
                <h3 class="text-label text-midnightBlue font-bold mb-4"> Desarrollo Personal </h3>
                <p class="text-lg"> Fomentar un vínculo estrecho entre <br /> padres de familia e hijos. </p>
              </div>

            </div>
            <div class="flex justify-between">
              <div class="w-1/2">
                <img src="~assets/ayuda-icon.png" />
                <h3 class="text-label text-midnightBlue font-bold mb-4"> Ayuda Docente </h3>
                <p class="text-lg"> Cuenta con un acompañamiento docente <br /> especializado. </p>
              </div>

              <div class="w-1/2">
                <img src="~assets/material-icon.png" />
                <h3 class="text-label text-midnightBlue font-bold mb-4"> Material de Trabajo </h3>
                <p class="text-lg"> Entrega de materiales para el desarrollo <br />de las actividades. </p>
              </div>

            </div>
          </div>
        </div>
      </section>

      <!-- 3rd Sections -->
      <section class="w-full px-10 pb-24 bg-pattern-2">
        <div class="text-center mb-16">
          <h2 class="text-coral text-4xl font-bold"> ¿Cómo funciona guía preesco? </h2>
        </div>
        <div class="flex justify-between py-14">
          <div class="w-1/2 px-14 flex justify-center items-center">
            <p class="text-2xl"> A cada alumno se le asigna una cuenta de correo <br /> institucional a través de la
              cual, la
              familia ingresará <br /> a Google Classroom.
              <br /><br />
              Con la ayuda de ROB-R2, podrán conocer las <br /> misiones semanales a completar.
              <br /><br />
              Semanalmente se realizará una videoconferencia <br /> con padres de familia por medio de Google Meet. </p>
          </div>

          <div class="w-1/2 flex justify-center">
            <img src="~assets/robo-placeholder.png" />
          </div>
        </div>
      </section>

      <!-- Section 4 -->
      <section class="w-full px-10">
        <div class="flex justify-between py-14">

          <div class="w-2/4 flex justify-center">
            <img src="~assets/robo-placeholder.png" />
          </div>

          <div class="w-2/4 px-14 flex flex-col justify-start items-start">
            <h2 class="text-coral text-4xl font-bold mb-7"> ¿Costos y el proceso de inscripción? </h2>
            <p class="text-lg mb-12"> Llenar los formularios correspondientes con toda la información del <br /> alumno
              y la familia..
              <br /><br />
              Enviar los documentos oficiales para generar su registro en nuestro<br /> sistema.
              <br /><br />
              Los padres de familia recibirán al correo que hayan indicado, la <br /> información para activar su
              cuenta.
              <br /><br />
              Los pagos de mensualidades deberán “domiciliarse” de su cuenta <br /> bancaria a la delnstituto.
            </p>
            <button
              onclick="window.location.href='https://sites.google.com/ipefh.edu.mx/guiapreescoipefh/formularios?authuser=0'"
              class="focus:ring-4 focus:outline-non mr-6 font-bold whitespace-nowrap inline-flex items-center justify-center px-3 md:px-5 py-2 border border-transparent rounded-md shadow-sm text-base text-white bg-coral hover:bg-coral">
              Inscríbelo Hoy &nbsp; <i data-feather="arrow-right"></i>
            </button>
          </div>
        </div>
      </section>
      <!-- Section Pay -->
      <section class="w-full px-10">
        <div class="flex justify-around py-14">
          <div class="flex justify-center items-center">
            <h2 class="font-bold text-4xl">Precios</h2>
          </div>
          <div class=" px-12 py-7 flex rounded-2xl bg-floralWhite items-center ">
            <h4 class="font-bold text-2xl px-2">Valle de Toluca <span class="text-3xl">$1,500 </span></h4>
            <span class="font-bold text-2xl px-8"> / </span>
            <h4 class="font-bold text-2xl px-2">Interior de la República <span class="text-3xl">$1,800 </span></h4>
          </div>
        </div>
      </section>
      <!--  Footer -->
      <Footer />
    </main>
  </div>
</template>

<script>
  export default {
    head: {
      script: [{
          src: "https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js",
        },
        {
          src: "https://unpkg.com/feather-icons"
        }
      ]
    },
    mounted() {
      feather.replace();
    }
  }

</script>

<style>
  /* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
  .bg-pattern-1 {
    background: url('~assets/test.png');
    background-size: cover;
  }

  .bg-pattern-2 {
    background: url('~assets/test-2.png');
    background-size: cover;
  }

  .bg-pattern-3 {
    background: url('~assets/test.png');
    background-size: cover;
  }

</style>
