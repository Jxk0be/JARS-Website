<svelte:head>
   <title>Contact Us</title>
</svelte:head>

<script>
    import Navbar from '/src/components/Navbar.svelte'
    import Footer from '/src/components/Footer.svelte'
</script>


<Navbar />

<div class="w-full h-full text-black flex flex-col items-center text-center bg-white pb-[10vh]">
    <h1 class="font-bold text-[27px] md:text-[35px] uppercase mt-[10vh]">Contact Us</h1>
    <div class="grid text-white grid-cols-1 gap-y-14 md:px-[4vw] lg:px-[15vw] w-full h-full mt-[3vh] font-['Raleway']">

        <div class="flex flex-col transition ease-in-out duration-200 items-center justify-center w-full z-20 drop-shadow-[-5px_15px_15px_rgba(0,0,0,0.45)]">
            <div class="bg-[#36393e] md:hover:bg-[#282b30] duration-200 transition ease-in-out md:w-[700px] text-center md:h-[515px] w-[350px] h-[750px] relative">
                    <h1 class="mt-5 text-3xl font-semibold px-16 mb-6">JARS Contact Information</h1>
                    <div class="mx-5 text-xl font-medium text-start">
                        <p class="pb-[1vh]">
                            To add yourself to our email list, give us feedback, or any other 
                            inquiry relating to the club, please reach out via email.
                        </p>
                        <div class="flex justify-center flex-col items-center">
                            <h1 class="pb-[4vh]"><span class="underline">Club Email</span> - jars@utk.edu</h1>
                        </div>

                        <p class="pb-[1vh]">
                            For all emergencies (e.g. getting locked out) or for any specific reason you 
                            would like to talk directly to the president, please use this email.
                        </p>
                        <div class="flex justify-center flex-col items-center">
                            <h1 class="pb-[4vh] text-center"><span class="underline">President Email</span> - ubasu1@utk.edu</h1>
                        </div>

                        <p class="pb-[1vh]">
                            If you would like to get into contact with our PR officer, please 
                            use this email or add this discord.
                        </p>
                        <div class="flex justify-center flex-col items-center">
                            <h1><span class="underline text-center">Email</span> - bwalte11@vols.utk.edu</h1>
                            <h1><span class="underline text-center">Discord</span> - Doc#1443</h1>

                        </div>
                    </div>
            </div>
            <div class="bg-[#282b30] w-[350px] h-[50px] md:w-[700px] flex justify-center items-center">
                <a href="https://discord.com/invite/eQfNkfs9pT" target="_blank" class="text-xl font-semibold uppercase underline hover:text-[#dfdcdd] ">JOIN OUR DISCORD</a>
            </div>
        </div>
    </div>
</div>

<Footer />