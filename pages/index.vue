<template>
  <b-container>
    <b-row>
      <b-col cols="5" class="mx-auto">
        <weather-card />
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import WeatherCard from '~/components/pages/weather/index.vue'
export default {
  components: {
    WeatherCard
  }
}
</script>
