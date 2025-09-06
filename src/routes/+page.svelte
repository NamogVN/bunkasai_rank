<script lang="ts">

    import Header from "$lib/header.svelte"

    import { goto } from '$app/navigation';
    import { fade } from 'svelte/transition';

</script>

<Header />

<title>J2A文化祭ランキング</title>

<main class="bg-gray-50 h-screen w-full pt-20" transition:fade={{ duration: 150 }}>
    <div class="lg:flex justify-center md:p-5 sm:p-5 lg:gap-[200px] md:gap-20 sm:gap-20">

        <button on:click={() => goto('/Allranking')} class="rounded-4xl lg:h-100 lg:w-100 md:h-100 md:w-100 sm:h-50 sm:w-50 drop-shadow-md bg-white p-5
                    hover:scale-105 transition-transform duration-300">

            <h1 class="grid grid-flow-col justify-items-center text-4xl font-bold pb-3">👑総合ランキング👑</h1>

            <div class=" bg-gray-200 rounded-4xl h-[300px] w-full">
                <img src="https://placehold.jp/150x150.png" class="rounded-2xl mx-auto"/>
            </div>
            
        </button>

        <button on:click={() => goto('/Taikoranking')} class="rounded-4xl lg:h-100 lg:w-100 md:h-100 md:w-100 sm:h-50 sm:w-50 drop-shadow-md bg-white p-5
                    hover:scale-105 transition-transform duration-300">

            <h1 class="grid grid-flow-col justify-items-center text-4xl font-bold pb-3">🥁太鼓ランキング🥁</h1>

            <div class=" bg-gray-200 rounded-4xl h-[300px] w-full">
                <img src="https://placehold.jp/150x150.png" class="rounded-2xl mx-auto"/>
            </div>

        </button>

    </div>
</main>