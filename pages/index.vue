<template>
    <div class="container flex flex-col p-3">
        <!-- navbar -->
    <div class="p-6 ">
        <div class="flex justify-between p-3">
            <p class="text-lg">Inayat Haji</p>
            <div class="flex gap-12 mr-20 text-lg">
                <button class="w-[100px]"
      :style="{ color: selectedItem === 'Home' ? '#6153BD' : '', textDecoration: selectedItem === 'Home' ? 'underline' : '' }"
      @click="selectItem('Home')"
    >Home</button>
    <button class="w-[100px]"
    :style="{ color: selectedItem === 'Projects' ? '#6153BD' : '', textDecoration: selectedItem === 'Projects' ? 'underline' : '' }"
      @click="selectItem('Projects')"
    >Projects</button>
    <button class="w-[100px]"
    :style="{ color: selectedItem === 'About' ? '#6153BD' : '', textDecoration: selectedItem === 'About' ? 'underline' : '' }"
      @click="selectItem('About')"
    >About</button>
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
        <div class=" flex flex-col w-full items-center mt-10">
            <h3 class="text-5xl font-semibold">Projects</h3>
            <span  class="h-1 mt-2 rounded-lg w-[100px] bg-[#6153bd]"></span>
        </div>
        <div class="">
            <div class="flex mt-10 w-full justify-between p-10">
                <img src="~/assets/svgs/card1.svg" class="h-[55vh] w-{45vw]" />
                <img src="~/assets/svgs/card2.svg" class="h-[57vh] w-{45vw]" />
                <img src="~/assets/svgs/card3.svg" class="h-[54vh] w-{45vw]" />
            </div>
            <div class="flex  w-full justify-center">
                <img src="~/assets/svgs/card4.svg" class="h-[48vh] w-{40vw]" />
            </div>
        </div>
        <div class=" flex flex-col w-full items-center mt-10">
            <div class="flex gap-3">
                <h3 class="text-5xl font-semibold">About</h3>
                <h3 class="text-5xl text-[#6153BD] font-semibold">me</h3>
            </div>
            <span  class="h-1 mt-2 rounded-lg w-[100px] bg-[#6153bd]"></span>
        </div>
        <div class="mb-8  gap-8 p-3 flex justify-between ">
            
            <div class=" h-[70vh] w-[1000px]">
                <img src="~/assets/svgs/about.svg" class="h-[65vh] w-[1000px]" />
            </div>
            <div class="flex flex-col gap-5 w-[800px] h-[50vh]">
                <h6 class="text-4xl ">Get to know me</h6>
                <p class="text-[#828282] text-3xl font-extralight text-xl h-[90px]">My journey into UI/UX began while I was working at a bank. While conducting a user survey, I realised that users had many pain points that were not being addressed. This led me to teach myself UI/UX and volunteer to help the company's design team with my findings and possible design solutions....</p>
                <p class="text-xl text-[#555555] mt-7 font-semibold">Read more</p>
                <h2 class="text-2xl ">Tools I use for Design</h2>
                <div class="bg-gradient-to-r from-[#7850CD] to-[#FBCCC4] h-[58px] p-[2px]  text-lg w-fit rounded-3xl">
                    <Button label="Figma" class="h-[42px] bg-white  text-lg w-fit  px-4 rounded-3xl"/>

                </div>
                <div class="bg-gradient-to-r from-[#7850CD] to-[#FBCCC4] h-[58px] p-[2px]  text-lg w-fit rounded-3xl">
                    <Button label="Miro" class="h-[42px] bg-white  text-lg w-fit  px-4 rounded-3xl"/>

                </div>
                <div class="bg-gradient-to-r from-[#7850CD] to-[#FBCCC4] h-[58px] p-[2px]  text-lg w-fit rounded-3xl">
                    <Button label="Notion" class="h-[42px] bg-white  text-lg w-fit  px-4 rounded-3xl"/>

                </div> <div class="bg-gradient-to-r from-[#7850CD] to-[#FBCCC4] h-[58px] p-[2px]  text-lg w-fit rounded-3xl">
                    <Button label="Adobe Illustrator" class="h-[42px] bg-white  text-lg w-fit  px-4 rounded-3xl"/>

                </div> <div class="bg-gradient-to-r from-[#7850CD] to-[#FBCCC4] h-[58px] p-[2px]  text-lg w-fit rounded-3xl">
                    <Button label="Adobe Photoshop" class="h-[42px] bg-white  text-lg w-fit  px-4 rounded-3xl"/>

                </div> 
                

                <p class="text-xl">Got a project in mind? Let’s talk!</p>
                <div class="flex gap-2">
                    <img src="~/assets/svgs/email.svg" class="h-7 w-10" />
                    <img src="~/assets/svgs/linkedin.svg" class="h-7 w-10" />

                </div>
            </div>
        </div>
        
    </div>
        <!-- Footer section -->

    <div class=" flex flex-col items-center mt-40">
        <div class=" flex justify-center gap-5">
            <img src="~/assets/svgs/web.svg" class="h-11 w-12 mt-1" />
            <img src="~/assets/svgs/email.svg" class="h-12 w-12" />
            <img src="~/assets/svgs/be.svg" class="h-10 w-10 mt-1" />
            <img src="~/assets/svgs/linkedin.svg" class="h-12 w-12" />
        </div >
        <p class='text-gray-500 font-thin text-sm p-4 items-center'>Inayat Haji 2024</p>
    </div>
    </div>
    </template>
    <script setup>
    import Button from 'primevue/button';
     const selectedItem = ref('');

    const selectItem = (item) => {
      selectedItem.value = item;
    };
    </script>