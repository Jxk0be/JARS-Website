<svelte:head>
    <title>Our Events</title>
</svelte:head>

<script>
    import Navbar from '/src/components/Navbar.svelte'
    import Footer from '/src/components/Footer.svelte'
</script>

<Navbar />

<div class="bg-white flex flex-col h-full w-full justify-center items-center pb-[8vh]">
    <h1 class="font-bold text-[27px] md:text-[35px] uppercase mt-[10vh] text-black text-center">Club Events</h1>
    <div class="grid grid-cols-1 gap-y-14 w-[350px] md:w-[700px] h-full mt-[3vh] font-['Raleway']">
        
        <div class="bg-[#36393e] flex flex-col items-center md:hover:bg-[#282b30] duration-200 transition ease-in-out w-full h-[615px] md:h-[360px] drop-shadow-[-5px_15px_15px_rgba(0,0,0,0.45)] rounded-3xl">
            <h1 class="mt-5 text-2xl font-bold px-16 mb-6">Weekly Thursday Club Meeting</h1>
            <div class="mx-5 text-xl font-medium text-start">
                <ul class="mb-3">
                    <li>When: 7:30 PM</li>
                    <li>Where: Strong Hall 105</li>
                </ul>
                <p class="mb-3">
                    Officially we are the <span class="underline">Japanese Animanga Research Society</span>, which is a 
                    rather fancy title for what essentially amounts to an <span class="underline">anime-manga club</span> 
                    at the University of Tennessee-Knoxville. 
                </p>
            </div>
        </div>

        <div class="bg-[#36393e] flex flex-col items-center md:hover:bg-[#282b30] duration-200 transition ease-in-out w-full h-[480px] md:h-[300px] drop-shadow-[-5px_15px_15px_rgba(0,0,0,0.45)] rounded-3xl">
            <h1 class="mt-5 text-2xl font-bold px-16 mb-6 text-center">Where have we been?</h1>
            <div class="mx-5 text-xl font-medium text-start">
                <p class="mb-3">
                    JARS, due to a variety of factors including the pandemic and perhaps 
                    slight mismanagement, hasn’t really existed for several years. It existed 
                    to some extent on discord with occasional online meetings, but this was 
                    merely a former shadow of itself.
                    <br> <br>
                    JARS and its IRL meetings were <span class="underline">revived in 2022</span> and we’re glad to be back in business. 
                </p>
            </div>
        </div>

        <div class="bg-[#36393e] flex flex-col items-center md:hover:bg-[#282b30] duration-200 transition ease-in-out w-full h-[560px] md:h-[330px] drop-shadow-[-5px_15px_15px_rgba(0,0,0,0.45)] rounded-3xl">
            <h1 class="mt-5 text-2xl font-bold px-16 mb-6 text-center">What are meetings like?</h1>
            <div class="mx-5 text-xl font-medium text-start">
                <p class="mb-3">
                    Typically, we play a quick game of animanga related kahoot. After which 
                    we may watch 1-2 anime episodes (this season it seems we are watching 
                    Chainsaw Man together). And then we have a “special activity” 
                    which changes every week. 
                    <br> <br>
                    You’re free and encouraged to chitchat, 
                    vibe, play video games, etc during meetings if you want. 
                    <span class="underline">Having a good time and rolling on the floor laughing is our 
                    ultimate goal</span>.
                </p>
            </div>
        </div>

        <div class="bg-[#36393e] flex flex-col items-center md:hover:bg-[#282b30] duration-200 transition ease-in-out w-full h-[390px] md:h-[250px] drop-shadow-[-5px_15px_15px_rgba(0,0,0,0.45)] rounded-3xl">
            <h1 class="mt-5 text-2xl font-bold px-16 mb-6 text-center">Where do y’all meet?</h1>
            <div class="mx-5 text-xl font-medium text-start">
                <p class="mb-3">
                    We generally meet in <span class="underline">Strong Hall 105 at 7:30 on Tuesdays</span> 
                    (our normal meetings) <span class="underline">and Thursdays</span> (movie-watching/manga discussions). 
                    However, this is subject to change.
                    <br> <br>
                    We will also keep you updated on the discord so please
                    <a class="hover:text-[#f51f43] underline font-semibold text-[#E94560]" href="https://discord.com/invite/eQfNkfs9pT" target="_blank">join us</a>!!
                </p>
            </div>
        </div>

    </div>
</div>

<Footer />