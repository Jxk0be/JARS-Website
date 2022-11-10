<svelte:head>
   <title>About Us</title>
</svelte:head>

<script>
    import Navbar from '/src/components/Navbar.svelte'
    import Footer from '/src/components/Footer.svelte'
    import image from '/src/images/boring_gf.jpg'
</script>

<Navbar />
<div class="w-full h-full text-black flex flex-col items-center text-center bg-white pb-[10vh]">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <!-- <img class="object-cover h-full w-full absolute z-10" src={image} alt="bg-image" /> -->
    <h1 class="font-bold text-[27px] md:text-[35px] uppercase mt-[10vh]">About JARS</h1>
    <div class="grid text-white grid-cols-1 gap-y-14 md:px-[4vw] lg:px-[15vw] w-full h-full mt-[3vh] font-['Raleway']">

        <div class="flex flex-col transition ease-in-out duration-200 items-center justify-center w-full z-20 drop-shadow-[-5px_15px_15px_rgba(0,0,0,0.45)]">
            <div class="bg-[#36393e] md:hover:bg-[#282b30] duration-200 transition ease-in-out md:w-[700px] md:h-[515px] w-[350px] h-[750px] relative">
                    <h1 class="mt-5 text-3xl font-semibold px-16">Who are we?</h1>
                    <h1 class="text-xl font-medium mb-6">Made by JARS</h1>
                    <div class="mx-5 text-xl font-medium text-start">
                        <p class="mb-3">
                            Ohayō おはよう and welcome to the best anime club on campus. 
                            JARS is the Japanese Anime “Research” Society—we don’t 
                            actually do research though. Here you can chat and 
                            relax with people of culture—weebs. 
                        </p>
                        <p class="mb-3">Together we’ll 
                            watch the newest anime, hang out for mini field trips 
                            (rides provided), and share (and roast) our favorite 
                            anime and manga. If you’re looking for a chill, cat-loving 
                            club to network with people who share a love for Japanese 
                            entertainment, join JARS! 
                            <br><br>
                            ♡∩_∩ <br>
                            （„• ֊ •„)♡<br>
                            ┏━━━━━━━┓
                            <br>
                            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            <a class="hover:text-[#f51f43] underline text-[#E94560]" href="https://discord.com/invite/eQfNkfs9pT" target="_blank">our discord</a><br>
                            ┗━━━━━━━┛
                        </p>
                    </div>
            </div>
            <div class="bg-[#282b30] w-[350px] h-[50px] md:w-[700px] flex justify-center items-center">
                <h1 class="text-xl font-semibold uppercase">INSERT NUTS OR NOTHING LOGO</h1>
            </div>
        </div>
    </div>
</div>
<Footer />
