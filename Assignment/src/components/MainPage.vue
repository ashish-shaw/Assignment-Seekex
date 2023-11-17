<template>
    <section>
        <Header/>
        <Navbar/>
        <img :src="image1" class="w-full" />
        <div class="flex sm:px-28 px-3 sm:py-14 py-6 sm:justify-between space-x-2">
            <div v-for="(item,index) in collections" :key="index">
                <img :src="item.image" />
                <h3 class="sm:font-semibold font-light sm:text-base text-xs">{{item.label}}</h3>
            </div>
        </div>
        <Collections/>
        <Trending/>
        <Featured />
        <img :src="banner1" class="w-full py-10" />
        <NewProducts/>
        <BestSelling/>
        <ShirtCollections/>
        <img :src="banner2" class="w-full sm:py-10 py-3" />
        <Discount/>
        <ReturnSection/>
        <div class="border-b py-5"></div>
        <Footer/>
    </section>
</template>
<script setup>
import Header from './Header.vue'
import Navbar from './Navbar.vue'
import Collections from './Collections.vue'
import Trending from './Trending.vue'
import Featured from './Featured.vue'
import NewProducts from './NewProducts.vue'
import BestSelling from './BestSelling.vue'
import ShirtCollections from './ShirtCollections.vue'
import Discount from './Discount.vue'
import ReturnSection from './ReturnSection.vue'
import Footer from './Footer.vue'
import image1 from './Images/image1.png'
import image2 from './Images/image2.png'
import image3 from './Images/image3.png'
import image4 from './Images/image4.png'
import image5 from './Images/image5.png'
import image6 from './Images/image6.png'
import image7 from './Images/image7.png'
import banner1 from './Images/banner1.png'
import banner2 from './Images/banner2.png'

const collections = [{
            image: image2,
            label: 'Men’s T-Shirts'
            },
            {
            image: image3,
            label: 'Women’s Wear'
            },
            {
            image: image4,
            label: 'Hooded T-Shirts'
            },
            {
            image: image5,
            label: 'Polo Neck T-Shirts'
            },
            {
            image: image6,
            label: 'Full Sleeves T-Shirts'
            },
            {
            image: image7,
            label: 'Winter Collections'
            },
            ]

</script>
