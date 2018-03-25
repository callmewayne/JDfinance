<template lang="html">
    <div >
        <Heador />
        <Slider />
        <Novice />
        <Borrow />
        <Money />
        <Product />
        <Life />
        <CampanyInfo />
        <NavBar />
    </div>
</template>

<script>
import Heador from "../public/header.vue";
import Slider from "./hSlider.vue";
import Novice from "./novice.vue";
import Borrow from "./borrow.vue";
import Money from "./money.vue";
import Product from './product.vue';
import Life from './life.vue';
import CampanyInfo from '../public/footer.vue';
import NavBar from '../public/navbar.vue'
export default {
  components: {
    Heador,
    Slider,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    CampanyInfo,
    NavBar
  }
};
</script>

<style lang="scss" module>

</style>
