<svelte:head>
    <title>JARS</title>
</svelte:head>

<script>
    import Navbar from '../components/Navbar.svelte'
    import Hero from '../components/Hero.svelte';
</script>

<Navbar />
<Hero />

<div class="w-full h-[70vh] bg-red-100 flex flex-col items-center text-center">
    <h1 class="mt-[5vh] text-[25px] font-semibold mb-5">Announcements</h1>
    <div class="grid grid-cols-1 w-full gap-y-10">
        <div class="w-[full] h-[50vh] bg-red-300 mx-[10vw] rounded-xl flex flex-col items-center text-center">
            <h1 class="mt-4 text-xl">September 15, 2022</h1>
        </div>
    </div>
</div>
