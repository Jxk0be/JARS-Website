<script>
    import Typewriter from 'svelte-typewriter'
    import heroVid from '../Images/hero_video.mp4'
    import heroVid2 from '../Images/hero_video2.mp4'
</script>


<div class="h-[92vh] w-full">
    <video class="object-cover h-full w-full absolute z-10" src={heroVid2} autoplay loop muted />
    <div class="z-20 w-full h-[100vh] flex flex-col justify-center items-center text-center bg-black/30 absolute">
        <div class="z-20">
            <h1 class="md:text-6xl font-bold text-[37px] md:mx-[100px] gamer uppercase drop-shadow-[0px_10px_15px_rgba(0,0,0,0.75)]">Japanese Animanga Research Society</h1> 

            <div class="flex flex-row justify-center items-center md:text-3xl text-xl md:font-bold font-bold font-['Raleway'] drop-shadow-[0px_10px_15px_rgba(0,0,0,0.75)]">
                &#8205;
                <Typewriter mode="loop" interval={[66, 76, 74, 70, 63, 54, 63, 64, 74, 64]} cursor={false}>
                    <h1>Watch anime...</h1>
                    <h1>Read manga...</h1>
                    <h1>Hangout with friends...</h1>
                </Typewriter>
            </div>
        </div>
    </div>
</div>
