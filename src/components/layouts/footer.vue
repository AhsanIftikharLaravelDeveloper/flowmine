<template>
    <footer class="border-t px-8 py-3 flex flex-col md:flex-row justify-between items-start md:items-center w-full gap-3">
        <router-link to="/" activeClass="home" class="hover:bg-transparent">
            <h2 class="uppercase text-custom-orange custom-logo">FlowBlaze</h2>
        </router-link>
        <div class="grid grid-cols-2 md:flex w-full md:w-max gap-0 md:gap-10">
            <router-link to="/pricing" activeClass="pricing"
                class="text-custom-gray tracking-widest leading-7 text-xs font-bold hover:text-[#FC6F43]">PRICING</router-link>
            <a href="javascript:void(0);"
                class="text-custom-gray tracking-widest leading-7 font-bold text-xs">ABOUT</a>
            <a href="javascript:void(0);"
                class="text-custom-gray tracking-widest leading-7 font-bold text-xs">CONTACT</a>
            <a href="javascript:void(0);"
                class="text-custom-gray tracking-widest leading-7 font-bold text-xs">PRIVACY</a>
        </div>
    </footer>
</template>