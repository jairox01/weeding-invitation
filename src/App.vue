<template>
  <HeaderComponent />
  <DateComponent />
  <ItineraryComponent />
  <MasonryComponent />
  <LocationComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import MasonryComponent from './components/MasonryComponent.vue'
import DateComponent from './components/DateComponent.vue'
import ItineraryComponent from './components/ItineraryComponent.vue'
import LocationComponent from './components/LocationComponent.vue'
import './assets/styles/main.scss'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MasonryComponent,
    DateComponent,
    ItineraryComponent,
    LocationComponent
  }
}
</script>

