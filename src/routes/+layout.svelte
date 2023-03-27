<script>
    import "virtual:windi.css"
</script>  

<div class="w-screen h-screen grid grid-cols-[14rem,auto] grid-rows-[70px,auto] overflow-hidden bg-light-400">
    <div class="row-span-2 bg-white p-6 border-r-gray-300 border-r">
        <img src="/nthu.png" class="w-16 h-16" alt="nthu logo"/>
        <div class="py-4">
            <h1 class="text-2xl font-semibold">國立清華大學</h1>
            <h1 class="text-lg font-semibold">NTHU</h1>
        </div>
        <div class="">
            <input type="text" class="w-full bg-gray-200 rounded-md py-2 px-4 text-sm font-semibold" placeholder="Quick Search (Ctrl + /)" />
            
        </div>
    </div>
    <div class="flex flex-row bg-white px-6 items-center">
        <h2 class="flex-1 text-xl font-bold">主頁 Dashboard</h2>
        <div class="grid grid-cols-[48px,auto] gap-3 place-items-center">
            <div class="grid place-items-center w-12 h-12">
                <img src="/nthu.png" class="" alt="user icon"/>
            </div>
            <div class="flex flex-col gap-1">
                <span class="font-semibold leading-none">丘子輝</span>
                <span class="text-sm font-semibold leading-none">Chew Tzi Hwee</span>
            </div>
        </div>
    </div>
    <div class="overflow-auto">
        <slot />
    </div>
</div>
