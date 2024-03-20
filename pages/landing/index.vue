<template>
<!-- navbar -->
<div class="flex justify-between p-3">
    <p>Inayat Haji</p>
    <div class="flex gap-5">
        <button>Home</button>
        <button>Projects</button>
        <button>About</button>
    </div>
</div>
<!--details section  -->
<div class="h-[65vh] w-[550px] p-3">
    <div class="flex flex-col gap-5">
        <h6 class="text-sm text-[#6153bd] font-semibold">PRODUCT DESIGNER</h6>
        <h1 class="text-6xl font-semibold">Hello, My name is</h1>
        <h2 class="text-5xl text-[#9489d0] font-semibold">some name</h2>
        <p class="text-[#828282] text-3xl">A dreamer and Creative Product Designer</p>
        <p class="text-gray-500 text-xs text-xl">I utilize user-centric design and my empathetic skills to create visually stunning and user-friendly interfaces that resonate with your target market.</p>
        <div class="flex">
            <Button />
        </div>
    </div>
    <div>

    </div>
</div>
</template>
<script setup>
import Button from 'primevue/button';
</script>