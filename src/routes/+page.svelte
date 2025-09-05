<script>

    import Header from "$lib/header.svelte"

</script>

<Header />

<main class="bg-gray-50 h-screen w-full pt-20">
    <div class="lg:flex justify-center md:grid justify-items-stretch md:p-5 sm:p-5 lg:gap-[200px] md:gap-20 sm:gap-20">

        <div class="rounded-4xl lg:h-100 lg:w-100 md:h-100 md:w-100 sm:h-50 sm:w-50 drop-shadow-md bg-white p-5
                    hover:scale-105 transition-transform duration-300">

            <h1 class="grid grid-flow-col justify-items-center text-4xl font-bold pb-3">👑総合ランキング👑</h1>

            <div class=" bg-gray-200 rounded-4xl h-[300px] w-full">
                <img src="https://placehold.jp/150x150.png" class="rounded-2xl mx-auto"/>
            </div>
            
        </div>

        <div class="rounded-4xl lg:h-100 lg:w-100 md:h-100 md:w-100 sm:h-50 sm:w-50 drop-shadow-md bg-white p-5
                    hover:scale-105 transition-transform duration-300">

            <h1 class="grid grid-flow-col justify-items-center text-4xl font-bold pb-3">🥁太鼓ランキング🥁</h1>

            <div class=" bg-gray-200 rounded-4xl h-[300px] w-full">
                <img src="https://placehold.jp/150x150.png" class="rounded-2xl mx-auto"/>
            </div>
                
        </div>

    </div>
</main>