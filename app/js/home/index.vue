<template lang="html">
    <div>
        <Header/>
        <Slider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Product/>
        <Life/>
        <Footer/>
        <Navbar/>
    </div>

</template>

<script>
import Header from "../public/header"
import Slider from '../home/hslider'
import Novice from '../home/novice'
import Borrow from '../home/borrow'
import Money from '../home/money'
import Product from '../home/product'
import Life from '../home/life'
import Footer from '../public/footer'
import Navbar from '../public/navbar'
export default {
    components: {
        Header,
        Slider,
        Novice,
        Borrow,
        Money,
        Product,
        Life,
        Footer,
        Navbar
    },
}
</script>

<style lang="scss" module>
</style>
