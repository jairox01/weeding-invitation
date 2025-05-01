<template>
  <HeaderComponent />
  <DateComponent />
  <ItineraryComponent />
  <MasonryComponent />
  <LocationComponent />
  <DressCodeComponent />
  <FooterComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import MasonryComponent from './components/MasonryComponent.vue'
import DateComponent from './components/DateComponent.vue'
import ItineraryComponent from './components/ItineraryComponent.vue'
import LocationComponent from './components/LocationComponent.vue'
import DressCodeComponent from './components/DressCodeComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import './assets/styles/main.scss'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MasonryComponent,
    DateComponent,
    ItineraryComponent,
    LocationComponent,
    DressCodeComponent,
    FooterComponent
  }
}
</script>

