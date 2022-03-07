<template>
  <div class="q-pa-md">
    <q-layout view="lHh Lpr lff">
      <q-header class="primary" style="height: 250px">
        <div style="display:table">
          <div class="col text-center text-white">Takemura andres</div>
          <div class="col text-center text-white">EDAD 28 AÑOS</div>
          <div class="col text-center text-white">RESIDEN EN SANTA FE CAPITAL</div>
          <div class="col text-center text-white">email: takemura_an@hotmail.com.ar</div>
          <div class="col-6 text-center text-white">facebook: /andres.takemura</div>
        </div>
      </q-header>

      <q-drawer
        v-model="drawer"
        show-if-above
        :width="200"
        :breakpoint="400"
      >
        <q-scroll-area style="height: calc(100% - 250px); margin-top: 250px; border-right: 1px solid #ddd">
          <q-list padding>
            <q-item clickable v-ripple to="/" exact>
              <q-item-section avatar>
                <q-icon name="inbox" />
              </q-item-section>

              <q-item-section>
                Home
              </q-item-section>
            </q-item>

            <q-item clickable v-ripple to="/certificados" exact>
              <q-item-section avatar>
                <q-icon name="star" />
              </q-item-section>

              <q-item-section>
                Certificados
              </q-item-section>
            </q-item>

            <q-item clickable v-ripple to="/CV" exact>
              <q-item-section avatar>
                <q-icon name="star" />
              </q-item-section>

              <q-item-section>
                CV propiamente dicho
              </q-item-section>
            </q-item>

          </q-list>
        </q-scroll-area>

        <q-img class="absolute-top" src="../img/fondodepantalla.jpeg" style="height: 250px">
          <div class="absolute-bottom bg-transparent">
            <q-avatar size="56px" class="q-mb-sm">
              <img src="../img/Yo.png">
            </q-avatar>
            <div class="text-weight-bold">Takemura Andres</div>
            <div class="text-weight-bold; color:primary">CUMBIA 420 PA LO NEGRO</div>
          </div>
        </q-img>
      </q-drawer>

      <q-page-container>
        <router-view />
      </q-page-container>
    </q-layout>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      drawer: ref(false)
    }
  }
}
</script>