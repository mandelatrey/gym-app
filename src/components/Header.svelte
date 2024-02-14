<script>
    import {openModal} from "../store"
</script>
<header class="w-screen self-center flex flex-col relative z-20 ">
    <div class="max-w-[1400px] mx-auto w-full bg-opacity-5 bg-blur duration-200 fadeIn bg-blend-multiply  backdrop-blur hover:opacity-7 bg-indigo-100 flex items-center justify-between p-4 py-6">
        <a href="/">
            <h1 class="font-semibold">iDear <span class="text-indigo-400">Gym+</span></h1>
        </a>
        <button on:click={() => ($openModal = true)} class="md:hidden grid place-items-center">
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center  gap-4 lg:gap-6">
            <a href="#product" class="duration-200 hover:text-indigo-400 cursor-pointer">Product</a>
            <a href="#reviews" class="duration-200 hover:text-indigo-400 cursor-pointer">Reviews</a>
            <a href="#faqs" class="duration-200 hover:text-indigo-400 cursor-pointer">FAQ</a>
            <button class="specialBtn">
                <p>Start Free Today</p>
            </button>
        </nav>
    </div>
</header>