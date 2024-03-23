<template>
<!-- navbar -->
<div class="p-6 h-[80vh]">
    <div class="flex justify-between p-3">
        <p class="text-lg">Inayat Haji</p>
        <div class="flex gap-12 mr-20 text-lg">
            <button>Home</button>
            <button>Projects</button>
            <button>About</button>
        </div>
    </div>
    <!--details section  -->
    <div class="h-[70vh]  gap-8 p-3 flex justify-between ">
        <div class="flex flex-col gap-5 w-[750px] h-full">
            <h6 class="text-lg text-[#6153bd] font-semibold">PRODUCT DESIGNER</h6>
            <h1 class="text-6xl font-semibold">Hello, My name is</h1>
            <h2 class="text-6xl text-[#9489d0] font-semibold">Inayat Haji</h2>
            <p class="text-[#828282] text-4xl py-3">A dreamer and Creative Product Designer.</p>
            <p class="text-[#828282] text-3xl font-extralight space-x-10 text-xl h-[100px]">I utilize user-centric design and my empathetic skills to create visually stunning and user-friendly interfaces that resonate with your target market.</p>
            <div class="flex gap-4">
                <Button label="Projects" class="h-[45px] bg-[#6153bd] text-white text-lg w-[120px] rounded-lg"/>
                <Button label="Linkedin" class="h-[45px] text-[#6153bd] bg-white font-medium border-2 border-[#6153bd] text-lg w-[120px] rounded-lg"/>

            </div>
        </div>
        <div class=" h-[50vh] w-[1000px]">
            <img src="~/assets/svgs/landing.svg" class="h-[65vh] w-{60vw]" />
        </div>
    </div>
</div>
</template>
<script setup>
import Button from 'primevue/button';
</script>