<template>
    <section :class="cname">
        <swiper :options="options" :not-next-tick="options.notNextTick">
            <swiper-slide v-for="item in items" :key="item.id">
                <router-link :to="item.href">
                    <img :src="item.src" alt="this is a picture">
                </router-link>
            </swiper-slide>
        </swiper>
        <div v-if="options.pagenation" class="swiper-pagination"/>
    </section>
</template>

<script>
import { swiper, swiperSlide } from "vue-awesome-swiper"
export default {
    components: {
        swiper,
        swiperSlide,
    },
    props: {
        options: {
            type: Object,
            default() {
                return {
                    autoplay: true,
                    loop: true,
                    pagination: {
                        el: ".swiper-pagination",
                    },
                    notNextTick: false,
                }
            },
        },
        items: {
            type: Array,
            default() {
                return []
            },
        },
        cname:{
            type: String,
            default: ""
        }
    },
}
</script>
<style lang='scss'>
    @import "~swiper/dist/css/swiper.css";
</style>
