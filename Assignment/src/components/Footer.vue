<template>
<div>
  <div class="sm:px-28 px-3 pt-10 flex sm:space-x-4 space-x-2">
    <div class="w-[24%]"> 
      <p class="font-medium sm:text-sm text-[10px]">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries....
      </p>
      <div class="flex sm:space-x-2 space-x-1 sm:py-4 py-1">
        <Facebook />
        <Twitter />
        <Instagram />
        <LinkedIn />
        <Interest />
      </div>
    </div>
    <div class="w-[24%] sm:pl-10 pl-3">
      <div class="text-[#770015] font-semibold sm:text-lg text-xs pb-4">
        ONLINE SHOPPING
      </div>
      <p class="font-medium sm:text-sm text-[10px] py-2">Men’s T-Shirts</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Women’s Wear</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Winter Collections</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Hooded T-Shirts</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Streetwear Collections</p>
    </div>
    <div class="w-[24%]">
      <div class="text-[#770015] font-semibold sm:text-lg text-xs pb-4">
        CUSTOMER POLICIES
      </div>
      <p class="font-medium sm:text-sm text-[10px] py2">About Us</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Terms & Conditions</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Shipping & Returns Policy</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Cancellation & Refund Policy</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Contact Us</p>
    </div>
    <div class="w-[24%]">
      <div class="text-[#770015] font-semibold sm:text-lg text-xs pb-4">
        STORE INFORMATION
      </div>
      <p class="font-medium sm:text-sm text-[10px] py2">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry.
      </p>
      <p class="font-medium sm:text-sm text-[10px] py-4">Call Us: 1234567890</p>
      <p class="font-medium sm:text-sm text-[10px] py-2">Email Us: info@yourmail.com</p>
    </div>
  </div>
  <div class="bg-[#20050A] text-center font-medium sm:text-sm text-[10px] text-white sm:py-4 py-2">©2022-23 Powered By dummy team</div>
  </div>
</template>

<script setup>
import Facebook from "./Icons/Facebook.vue";
import Twitter from "./Icons/Twitter.vue";
import Instagram from "./Icons/Instagram.vue";
import LinkedIn from "./Icons/LinkedIn.vue";
import Interest from "./Icons/Interest.vue";
</script>
