<template lang="html">
    <div>
        <Header/>
        <Slider/>
        <Ada/>
        <Money/>
        <Adb/>
        <Finance/>
        <Adc/>
        <Footer cname="mfooter"/>
        <Navbar/>
    </div>

</template>

<script>
import Header from "../public/header"
import Slider from './mslider'
import Ada from './ada'
import Money from './money'
import Adb from './adb'
import Finance from './finance'
import Adc from './adc'
import Footer from '../public/footer'
import Navbar from '../public/navbar'

export default {
    components: {
        Header,
        Slider,
        Footer,
        Navbar,
        Ada,
        Finance,
        Adb,
        Money,
        Adc
    },
}
</script>

<style lang="scss">
    .mfooter{
        margin-top: 0!important;
        ul{
            li:first-child{
                display: none;
            }
        }
    }
</style>
