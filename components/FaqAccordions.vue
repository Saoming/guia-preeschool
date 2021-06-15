<template>
    <div class="border-2 border-gray-200 bg-white rounded hover:bg-gray-80 shadow-sm mb-12">
        <div class="py-12 px-8 flex items-center cursor-pointer" @click="showAccordion = !showAccordion">
            <!--Text   -->
            <div>
                <h4 class="text-2xl font-bold">
                    {{ title }}
                </h4>
            </div>
            <div>
                <svg width="98" height="97" viewBox="0 0 98 97" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M24.5 36.375L49 60.625L73.5 36.375" stroke="black" stroke-width="5" stroke-linecap="round"
                        stroke-linejoin="round" />
                </svg>
            </div>
        </div>
        <!--  Content py-16 px-8 bg-color-gray hidden -->
        <div class="py-16 px-8 bg-gray-300 hidden" :class="{ showAccordion: showAccordion }" >
            <p class="text-black text-lg"> {{ answer }} </p>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            default: "¿Qué es Guía Preesco IPEFH?"
        },
        answer: {
            type: String,
            default: "Es una modalidad educativa que aporta una guía para que los padres de familia puedan acompañar el desarrollo de los conocimientos, las habilidades y las actitudes de sus hijos correspondientes a su edad preescolar, de acuerdo al modelo educativo IPEFH."
        }
    },
    data() {
        return {
            showAccordion: false
        }
    }
}
</script>

<style>
    .showAccordion {
        display: block;
    }
    
</style>