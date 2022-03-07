<template>
  <q-page >
    <div>
       <h5 class="text-center">Aca van a ir todos los certificados... vamos a ver como se ven</h5>
    </div>
   
    <!-- <div v-for="(show, index) in certificados" :key="index">
      <ul> {{show.name}}  {{show.apellido}} </ul>
    </div> -->

     <div class="q-pa-md">
    <q-list bordered class="rounded-borders">
      <q-expansion-item
        expand-separator
        icon="perm_identity"
        label="Account settings"
        caption="John Doe"
      >
        <q-card>
          <q-card-section class="row">
            <div class="col-6">
              <q-img
              src="https://cdn.quasar.dev/img/parallax2.jpg"
              style="width: 100%"
              native-context-menu
              >
              <div class="absolute-bottom text-subtitle1 text-center">
                Caption
              </div>
              </q-img>
            </div>

            <div class="col-6">
              <q-img
              src="https://cdn.quasar.dev/img/parallax2.jpg"
              style="width: 100%"
              native-context-menu
              >
              <div class="absolute-bottom text-subtitle1 text-center">
                Caption
              </div>
              </q-img>
            </div>

            <div class="col-6">
              <q-img
              src="https://cdn.quasar.dev/img/parallax2.jpg"
              style="width: 100%"
              native-context-menu
              >
              <div class="absolute-bottom text-subtitle1 text-center">
                Caption
              </div>
              </q-img>
            </div>

            <div class="col-6">
              <q-img
              src="https://cdn.quasar.dev/img/parallax2.jpg"
              style="width: 100%"
              native-context-menu
              >
              <div class="absolute-bottom text-subtitle1 text-center">
                Caption
              </div>
              </q-img>
            </div>
          </q-card-section>
        </q-card>
      </q-expansion-item>

      <q-expansion-item
        expand-separator
        icon="signal_wifi_off"
        label="Wifi settings"
      >
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>

      <q-expansion-item
        expand-separator
        icon="drafts"
        label="Drafts"
        header-class="text-purple"
      >
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="drafts"
        label="Drafts"
        header-class="text-purple"
      >
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="drafts"
        label="Drafts"
        header-class="text-purple"
      >
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="drafts"
        label="Drafts"
        header-class="text-purple"
      >
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="drafts"
        label="Drafts"
        header-class="text-purple"
      >
        <q-card>
          <q-card-section>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
            commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
            eveniet doloribus ullam aliquid.
          </q-card-section>
        </q-card>
      </q-expansion-item>

    </q-list>
  </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PageIndex',
  data () {
    return {
    certificados: [
      { name: "no se", apellido: "no se cuanto"},
      { name: "no se2", apellido: "no se cuanto"},
      { name: "no se3", apellido: "no se cuanto"},
      { name: "no se4", apellido: "no se cuanto"}
    ]
   }
  }
})
</script>
