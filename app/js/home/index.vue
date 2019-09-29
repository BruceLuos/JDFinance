<template lang="html">
    <div>
        <Header/>
        <Slider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Product/>
    </div>

</template>

<script>
import Header from "../public/header"
import Slider from '../home/hslider'
import Novice from '../home/novice'
import Borrow from '../home/borrow'
import Money from '../home/money'
import Product from '../home/product'
export default {
    components: {
        Header,
        Slider,
        Novice,
        Borrow,
        Money,
        Product
    },
}
</script>

<style lang="scss" module>
</style>
