<script>
    import Icon from '@iconify/svelte';
    
    let mobileMenu = false;
    
    /* This function will handle most of the interaction with the mobile menu, except for the "Catch-all" function below */
    const HandleMenu = () => {
        mobileMenu = !mobileMenu;
    }

    /* Catch-all function to make sure some bugs don't arise from switching from mobile -> desktop view */
    const CloseMenu = () => {
        mobileMenu = false;
    }
</script>

<div class="flex flex-row items-center justify-between flex-nowrap z-20 fixed w-full bg-red-200 h-[8vh]">
    <!-- Section for the logo/name once that is all figured out -->
    <div class="ml-6 md:ml-12 font-['Raleway'] font-bold text-xl">
        <a on:click={() => CloseMenu()} href="/" class="hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer mx-4"><h1>JARS</h1></a>
    </div>

    <!-- Medium -> Large sized screens will have this style for the navbar -->
    <div class="flex-row justify-center items-center md:flex hidden no_wrap font-['Raleway'] font-medium text-xl">
        <a href="/" class="hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer mx-4"><h1>Home</h1></a>
        <a href="/about" class=" hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer mx-4"><h1>About</h1></a>
        <a href="/events" class=" hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer mx-4"><h1>Events</h1></a>
        <a href="/faq" class=" hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer mx-4"><h1>FAQ</h1></a>
        <a href="/contact" class=" hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer mx-4"><h1>Contact</h1></a>
        <a href="/support" class=" hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer ml-4 mr-12"><h1>Support Us</h1></a>
    </div>

    <!-- Rest of this div is for the mobile/small sized screens -->
    {#if mobileMenu === false}
        <div class="flex flex-row justify-center items-center mr-6 md:hidden" on:click={() => HandleMenu()}>
            <Icon icon="bx:menu" class="text-5xl cursor-pointer" />
        </div>
    {/if}

    {#if mobileMenu}
        <div class="flex flex-row justify-center items-center mr-6 md:hidden" on:click={() => HandleMenu()}>
            <Icon icon="bx:arrow-back" class="text-5xl cursor-pointer" />
        </div>
    {/if}
</div>

{#if mobileMenu}
    <div class="text-black font-['Raleway'] font-medium text-3xl fixed top-0 left-0 flex flex-col items-center justify-center text-center w-full h-screen bg-white md:hidden">
        <a on:click={() => HandleMenu()} href="/" class="my-4 mx-4 hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer"><h1>Home</h1></a>
        <a on:click={() => HandleMenu()} href="/about" class="my-4 mx-4 hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer"><h1>About</h1></a>
        <a on:click={() => HandleMenu()} href="/events" class="my-4 mx-4 hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer"><h1>Events</h1></a>
        <a on:click={() => HandleMenu()} href="/faq" class="my-4 mx-4 hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer"><h1>FAQ</h1></a>
        <a on:click={() => HandleMenu()} href="/contact" class="my-4 mx-4 hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer"><h1>Contact</h1></a>
        <a on:click={() => HandleMenu()} href="/support" class="my-4 mx-4 hover:text-[#00C896] transition ease-in-out duration-250 cursor-pointer"><h1>Support Us</h1></a>
    </div>
{/if}