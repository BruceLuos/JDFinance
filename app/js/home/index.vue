<template lang="html">
    <div>
        <Header/>
        <Slider/>
        <Novice/>
        <Borrow/>
        <Money/>
    </div>

</template>

<script>
import Header from "../public/header"
import Slider from '../home/hslider'
import Novice from '../home/novice'
import Borrow from '../home/borrow'
import Money from '../home/money'
export default {
    components: {
        Header,
        Slider,
        Novice,
        Borrow,
        Money
    },
}
</script>

<style lang="scss" module>
</style>
