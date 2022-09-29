<template>
    <div class="space-y-16">
        <div class="text-4xl font-bold">BraveVue Examples</div>

        <div class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
            <div class="pt-6">
                <router-link to="/draggable"
                    class="flow-root bg-zinc-100 dark:bg-zinc-900 group rounded-lg border-b-4 border-purple-500 px-6 pb-8 h-full">
                    <div class="-mt-6 text-center">
                        <div class="flex justify-center">
                            <span
                                class="group-hover:animate-spin inline-flex items-center rotate-45 text-white justify-center p-3 bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 rounded-md shadow-lg">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                    class="h-6 w-6" viewBox="0 0 16 16">
                                    <path fill-rule="evenodd"
                                        d="M7.646.146a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1-.708.708L8.5 1.707V5.5a.5.5 0 0 1-1 0V1.707L6.354 2.854a.5.5 0 1 1-.708-.708l2-2zM8 10a.5.5 0 0 1 .5.5v3.793l1.146-1.147a.5.5 0 0 1 .708.708l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 0 1 .708-.708L7.5 14.293V10.5A.5.5 0 0 1 8 10zM.146 8.354a.5.5 0 0 1 0-.708l2-2a.5.5 0 1 1 .708.708L1.707 7.5H5.5a.5.5 0 0 1 0 1H1.707l1.147 1.146a.5.5 0 0 1-.708.708l-2-2zM10 8a.5.5 0 0 1 .5-.5h3.793l-1.147-1.146a.5.5 0 0 1 .708-.708l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L14.293 8.5H10.5A.5.5 0 0 1 10 8z" />
                                </svg>
                            </span>
                        </div>
                        <h3 class="mt-8 text-xl uppercase font-bold text-gray-900 dark:text-zinc-300 tracking-wide">
                            Draggable</h3>
                        <p class="mt-3 text-base text-gray-600 dark:text-zinc-400">Brave Draggable is a Vue component
                            that helps you make
                            any element draggable with mouse or touch.</p>
                    </div>
                </router-link>
            </div>
        </div>
    </div>
</template>
