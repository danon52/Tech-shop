<template>
    <div class="w-full bg-black h-15">
        <div>
            <p class="text-white text-xl text-center py-5">Summer Sale For all Swim Suits And Free Express Delivery -
                OFF 50
                %! ShopNow
            </p>
        </div>
    </div>

    <header class="px-30 py-15">
        <div class="">
            <div>
            </div>
            <nav class="flex justify-between ">
                <p class="text-4xl font-bold ">Exclusive</p>

                <NuxtLink class="text-2xl py-2" to="/main">Home</NuxtLink>
                <NuxtLink class="text-2xl py-2" to="">Contact</NuxtLink>
                <NuxtLink class="text-2xl py-2" to="">About</NuxtLink>
                <NuxtLink class="text-2xl py-2" to="">sign Up </NuxtLink>
                <input class="w-80 h-10 border rounded-2xl mt-2 p-3 bg-gray-100" placeholder="What are you looking for?"
                    type="text">
                <div class="flex py-2">
                    <img class="w-10" src="/Cart1.svg" alt="">
                    <img class="ml-8 w-10" src="/Wishlist.svg" alt="">
                </div>

            </nav>

        </div>
        <div class="py-3"">
            <hr>
        </div>
    </header>
    <div class=" flex ">

        <div class=" px-20 ">
            <p class=" text-2xl ">Woman’s Fashion</p>
            <hr>
            <p class=" text-2xl py-2">Men’s Fashion</p>
            <hr>
            <p class="text-2xl ">Electronics</p>
            <hr>
            <p class="text-2xl py-2 ">Home & Lifestyle</p>
            <hr>
            <p class="text-2xl ">Medicine</p>
            <hr>
            <p class="text-2xl py-2">Sports & Outdoor</p>
            <hr>
            <p class="text-2xl ">Baby’s & Toys</p>
            <hr>
            <p class="text-2xl py-2 ">Groceries & Pets</p>
            <hr>
            <p class="text-2xl ">Health & Beauty</p>
        </div>

        <div class="flex justify-end px-30 ">
            <div class="w-[70rem]  bg-black h-130 rounded-2xl">
                <div class="grid grid-cols-2 gap-4">
                    <div class="py-25 px-25">
                        <div class="flex  ">
                            <img class="w-13" src="/apple.svg" alt="">
                            <p class="text-white py-3 px-5 text-3xl ">Iphone 14 Series </p>
                        </div>
                        <p class=" py-3 text-7xl text-white">Up to 10% off Voucher</p>
                        <NuxtLink class="text-2xl py-2 text-white " to="/main">Shop now </NuxtLink>
                    </div>
                    <div class="flex justify-end py-25">
                        <img class="w-[40rem]" src="/add.svg" alt="">
                    </div>
                </div>

            </div>
        </div>
        </div>


</template>
<script setup lang='ts'></script>