<template>
  <q-layout view="lHh Lpr lFf">

    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title>
          Jardim Botânico UFSM
        </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-footer elevated>
      <q-tabs class="bg-primary text-white shadow-2">
        <!--<q-route-tab name="profile" icon="ion-person" exact to="/profile" />-->
        <q-route-tab name="map" icon="ion-map" exact to="/" />
        <q-route-tab name="menu" icon="ion-menu" exact to="/menu" />
      </q-tabs>
    </q-footer>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainLayout'
})
</script>

<style>
.q-header {
  height: 50px
}

.q-footer {
  height: 50px
}
</style>

