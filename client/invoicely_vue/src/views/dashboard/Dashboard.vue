<template>
    <div class="page-dashboard">
        <div class="columns is-multiline">
            <div class="column is-12">
                <h1 class="title">Dashboard</h1>
                <PlanetChart/>
            </div>
        </div>
    </div>
</template>

<script>
import axios from 'axios'
import PlanetChart from '../../components/planectChart.vue'
export default {
    name: 'Dashboard',
    components: {
    PlanetChart
  },
    
}
</script>