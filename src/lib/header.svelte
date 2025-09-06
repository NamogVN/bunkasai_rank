<script lang="ts">

    import { goto } from '$app/navigation';

</script>

<header class="fixed top-0 left-0 w-full h-20 bg-red-400 flex items-center justify-center z-10 text-white">

    <a on:click={() => goto('/')} class="absolute left-5 text-2xl">

        <img src="https://img.icons8.com/?size=100&id=i6fZC6wuprSu&format=png&color=000000" alt="HomeLogo" class="h-10 w-10 p-1 bg-red-300 rounded-xl hover:bg-red-100 transition"/>

    </a>

    <h1 class="text-3xl font-bold">J2A文化祭ランキング</h1>

</header>
