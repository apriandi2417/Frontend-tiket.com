<template>
    <div class="home">
        <Navbar />
        <Selectin1 />
        <Selectin2 />
    </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Selectin1 from '@/components/Selection1.vue'
import Selectin2 from '@/components/Selection2.vue'

export default {
    name: 'HomeView',
    components: {
        Navbar,
        Selectin1,
        Selectin2,
    }
}
</script>

<style scoped>

</style>


