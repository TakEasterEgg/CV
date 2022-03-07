<template>
  <q-page class="" padding>
    <h5 class="text-primary text-weight-bold">Formacion academica</h5>
    <div class="row" v-for="(carrera, index) in academico" :key="index">

      <div class="col-8" >
        <p> <b> {{carrera.carrera}}</b>  <br>
          {{ carrera.descripcion }}
        </p>
      </div>
      <div class="col-4">
        <p class="text-center">{{ carrera.cursada }}</p>  
      </div>
    </div>

    <q-separator />

    <h5 class="text-primary text-weight-bold">Experiencia laboral</h5>
    <div class="row">

      <div class="col-8">
        <p> <b></b>  <br>
          
        </p>
      </div>
      <div class="col-4">
        <p class="text-center"></p>  
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageIndex',
  data () {
    return {
      academico: [
      {
        carrera: "Analista Industrial",
        descripcion: "blablablablablabla",
        cursada: "2020 - 2020"
      },
      {
        carrera: "Analista Industrial",
        descripcion: "blablablablablabla",
        cursada: "2020 - 2020"
      },
      {
        carrera: "Ingenieria en alimentos",
        descripcion: "blablablablablabla",
        cursada: "2020 - 2020"
      },
      {
        carrera: "Tecnico quimico",
        descripcion: "blablablablablabla",
        cursada: "2020 - 2020"
      }

      ],
      formacion: [
        {}
      ],
      habilidades:[
        {}
      ]
    }
  }
})
</script>
