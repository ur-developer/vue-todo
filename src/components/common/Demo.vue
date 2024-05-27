<template>
    <div id="root">
        <p>{{ originalPrice }}</p> 100
        <p>{{ doublePrice }}</p> 200
        <p>{{ triplePirce }}</p> 300
    </div>
</template>

<script>
import { mapGetters } from 'vuex';

export default {
    computed: {
        ...mapGetters(['originalPrice', 'doublePrice', 'triplePirce'])

        // originalPrice() {
        //     return this.$store.getters.originalPrice;
        // },
        // doublePrice() {
        //     return this.$store.getters.doublePrice;
        // },
        // triplePirce() {
        //     return this.$store.getters.triplePirce;
        // }
    }
}
</script>

<style>
</style>