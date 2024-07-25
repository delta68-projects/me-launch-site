<script>
    import {goto} from "$app/navigation";
    import {openModal} from "../store";
</script>

<header class="flex flex-col relative z-20">
    <div
        class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6"
    >
        <a href="/">
            <h1 class="font-bold">
                Khabaddi <span class="text-indigo-400">Tournament</span>
            </h1>
        </a>
        <button class="md:hidden grid place-items-center" on:click={() => ($openModal = true)}>
            <i class="fa-solid fa-bars"/>
        </button>
        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            <a class="duration-200 hover:text-indigo-400 cursor-pointer" href="#product">Products</a>
            <a class="duration-200 hover:text-indigo-400 cursor-pointer" href="#reviews">Reviews</a>
            <a class="duration-200 hover:text-indigo-400 cursor-pointer" href="#faqs">FAQs</a>
            <button class="specialBtn" on:click={() => goto("/scores")}>
                <p>Live scores</p>
            </button>
        </nav>
    </div>
</header>
