<template>
    <div class="bg-[#F5F4F2]">
        <div class="sm:px-56 px-6 py-4 flex">
            <div>
                <Return/>
                <p class="sm:text-base text-xs font-medium sm:pt-4 pt-2">7 Days Return</p>
            </div>
            <div class="bg-pink-200 w-0.5 h-28 m-auto mr-4"></div>
            <div>
                <Batch/>
                <p class="sm:text-base text-xs font-medium sm:pt-4 pt-2">Quality Products</p>
            </div>
            <div class="bg-pink-200 w-0.5 h-28 m-auto mr-4"></div>
            <div>
                <Payment/>
                <p class="sm:text-base text-xs font-medium sm:pt-4 pt-2">Safe Payment</p>
            </div>
            <div class="bg-pink-200 w-0.5 h-28 m-auto mr-4"></div>
            <div>
                <Helpline/>
                <p class="sm:text-base text-xs font-medium sm:pt-4 pt-2">24x7 Helpline</p>
            </div>
        </div>
    </div>
</template>

<script setup>
import Return from './Icons/Return.vue'
import Batch from './Icons/Batch.vue'
import Payment from './Icons/Payment.vue'
import Helpline from './Icons/Helpline.vue' 
</script>
