<svelte:head>
    <title>JARS</title>
</svelte:head>

<script>
    import Navbar from '../components/Navbar.svelte'
    import Hero from '../components/Hero.svelte';
</script>

<Navbar />
<Hero />

<div class="w-full bg-white flex flex-col items-center text-center mt-[15vh] z-0 mb-[6vh]">
    <h1 class="font-bold text-[33px] uppercase">Announcements</h1>
    <div class="grid grid-cols-1 gap-y-14 md:grid-cols-2 w-full h-full mt-[4vh] font-['Raleway']">
        <div class="flex flex-col items-center justify-center w-full drop-shadow-lg">
            <div class="bg-teal-100 w-[325px] h-[380px]">
                <h1 class="mt-5 text-2xl font-semibold">September 22, 2022</h1>
            </div>
            <div class="bg-teal-200 w-[325px] h-[50px] flex justify-center items-center">
                <h1 class="text-2xl font-bold uppercase">VOLink</h1>
            </div>
        </div>

        <div class="flex flex-col items-center justify-center w-full drop-shadow-lg">
            <div class="bg-teal-100 w-[325px] h-[380px]">
                <h1 class="mt-5 text-2xl font-semibold">September 22, 2022</h1>
            </div>
            <div class="bg-teal-200 w-[325px] h-[50px] flex justify-center items-center">
                <h1 class="text-2xl font-bold uppercase">VOLink</h1>
            </div>
        </div>
    </div>
</div>
