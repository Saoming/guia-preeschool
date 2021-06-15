<template>
  <div class="font-sans">
    <HeaderFAQ />
    <HeroSectionSmall>
      <div class="text-center">
        <h1 class="text-6xl font-bold"> Preguntas Frecuentes  </h1>
      </div>
    </HeroSectionSmall>
    <div class="max-w-7xl my-12 mx-auto p-8">
      <!-- Faq Content -->
      <FaqAccordions />
      <FaqAccordions title="¿A quiénes va dirigida?"
        answer="A familias con hijos en edad Preescolar que, por distintos motivos, deciden formarlos en casa y requieren una orientación para hacerlo de la manera más eficaz y divertida, asegurando que se logren los objetivos de desarrollo de los niños en cada etapa. " />
      <FaqAccordions title="¿Cómo funciona?"
        answer="A cada alumno se le asigna una cuenta de correo institucional a través de la cual, la familia ingresará a Google Classroom. En el aula virtual, con la ayuda de ROB-R2, podrán conocer las misiones semanales a completar, que permitirán que los niños logren los propósitos de aprendizaje establecidos." />
      <FaqAccordions
        title="¿Cuáles son los costos y cómo hacer el proceso de inscripción de mi hijo(a) para Guía Preesco IPEFH?"
        answer="La mensualidad para las familias que habitan en Valle de Toluca es de $1,500. Para familias al interior de la República, la mensualidad es de $1,800. No se requiere realizar ningún pago por concepto de inscripción. " />
    </div>
    <div class="max-w-screen-2xl mx-auto">
      <Footer />
    </div>
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
