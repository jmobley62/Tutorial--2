<template>
   <div class="w-full h-full font-pop text-white">
        <header class="container text-lg mx-auto">
            <div class="px-20">
                <div class="flex justify-between py-8">
                    <div>
                        <a href="#" class="font-bold">JaQuan.Mobley</a>
                    </div>
            
                    <nav class="space-x-12 pr-19.5 font-bold">
                        <a href="#">Military</a>
                        <a href="#">Gaming</a>
                        <a href="#">Career</a>
                        <a href="#"><button class="bg-blue-700 p-1 px-6 font-bold">Reach Me</button></a>
                    </nav>  
                </div> 
            </div>        
        </header>

        <section class="container mx-auto text-white mt-16 flex">

            <div>
                <img src="~static/man.png" class="w-3/4 h-5/6 absolute right-0" style=" z-index: -1;">
            </div>

            <div>

                <h1 class="justify-between font-black pt-36 pl-44 text-7xl">A venture.<br>Through Life.<br>And It's Phases.</h1>

            </div>

        </section>

        <section class="container text-white mx-auto w-full mt-96 pt-44">

            <div class="break-point ml-20"></div>

            <div class="justify-between pl-20">

                <h2 class="text-4xl font-black pb-4">My work</h2>

                <p class="">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ex voluptatibus doloremque quod voluptas<br>eaque debitis beatae voluptates exercitationem.</p>
                
            </div>

            <div class="items-center pl-20 mt-10 grid grid-cols-3 grid-flow-row gap-4">
                <div><img src="~static/crane.jpg"></div>
                <div><img src="~static/hat.jpg"></div>
                <div><img class="py-4 bg-black" src="~static/pc.jpg"></div>
                <div><img src="~static/crane.jpg"></div>
                <div><img src="~static/hat.jpg"></div>
                <div><img class="py-4 bg-black" src="~static/pc.jpg"></div>
                <div><img src="~static/crane.jpg"></div>
                <div><img src="~static/hat.jpg"></div>
                <div><img class="py-4 bg-black" src="~static/pc.jpg"></div>
            </div>
            
        </section>

        <section class="container mx-auto mt-48 pl-20">
            <div class="break-point"></div>

            <h2 class="text-4xl font-black pt-1 pb-4">Clients</h2>

            <p>I’ve had the pleasure of working with multiple Fortune 500 companies, designing and<br>implementing both frontend and backend.</p>



        </section>
    </div>
</template>

<style>

    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;800&display=swap');

    .break-point {

        background: #1D4ED8;
        width: 100px;
        height: 7px;
        border-radius: 2.5px;

    }
</style>