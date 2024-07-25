<script>
    import { goto } from "$app/navigation";
    export let dark;
</script>

<div class="flex items-center gap-4">
    <button class={"specialBtn " + (dark ? " bg-[#181b34]" : " ")}>
        <p class="text-base sm:text-lg md:text-xl">Sponsers</p>
    </button>

    <button class="specialBtnDark" on:click={() => goto("/scores")}>
        <p class="text-base sm:text-lg md:text-xl">Live Scores &rarr;</p>
    </button>
</div>
