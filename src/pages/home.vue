<template>
    <div class="space-y-16">
        <div class="text-4xl font-bold">BraveVue Examples</div>

        <div class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3 2xl:grid-cols-4">
            <div class="pt-6">
                <router-link to="/TabPanel"
                    class="flow-root bg-zinc-100 dark:bg-zinc-900 group rounded-lg border-b-4 border-purple-500 px-6 pb-8 h-full">
                    <div class="-mt-6 text-center">
                        <div class="flex justify-center">
                            <span
                                class="inline-flex items-center rotate-45 text-white justify-center p-3 bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 rounded-md shadow-lg">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                    class="h-6 w-6 -rotate-45" viewBox="0 0 16 16">
                                    <path
                                        d="M0 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V6zm6 3h4V5H6v4zm9-1V6a1 1 0 0 0-1-1h-3v4h3a1 1 0 0 0 1-1z" />
                                </svg>
                            </span>
                        </div>
                        <h3 class="mt-8 text-xl uppercase font-bold text-gray-900 dark:text-zinc-300 tracking-wide">
                            Tabs</h3>
                        <p class="mt-3 text-base text-gray-600 dark:text-zinc-400">Show Options from your Data and save
                            the result through v-model. The following is an brave tabs in action.</p>
                    </div>
                </router-link>
            </div>
        </div>
    </div>
</template>
