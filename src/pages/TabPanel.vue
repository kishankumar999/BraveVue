<template>
    <div class="text-4xl font-bold mb-10">Tabs Examples</div>
    <hr class="border-zinc-700 mb-10">

    <!-- /////////////////////////////////////////////////////////////// -->
    <!-- Tabs Example 1 -->
    <!-- /////////////////////////////////////////////////////////////// -->
    <div class="text-2xl font-bold mb-5">Tabs 1</div>

    <BraveTabs ref="bravetabref" class="overflow-hidden" tabsWrapperClass="flex bg-zinc-900 p-1 rounded-xl"
        tab-button-class="rounded-xl px-5 flex-1 cursor-pointer text-center duration-200"
        tab-button-active-class="rounded-xl bg-zinc-800 px-5 flex-1 cursor-pointer text-center duration-200 shadow-md"
        tabs-content-class="bg-zinc-900 mt-2 rounded-lg p-5" v-bind:tabs="['a','b','c','d', 'e', 'f']" initialTab="a">

        <!-- ================================================================ -->
        <!-- Board-A PANEL  -->
        <!-- ================================================================ -->
        <template #tab-head-a>
            <span class="uppercase">Tab-A</span>
        </template>
        <template #tab-panel-a>
            <div class="text-xl mb-4 capitalize">Tab-A</div>
            <div>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam consequuntur cumque perferendis
                molestiae optio consectetur quis illo voluptatem voluptatibus, ut odio expedita reiciendis blanditiis
                provident laudantium animi qui velit soluta maiores sed ducimus omnis. Reprehenderit tempore voluptate
                quo velit optio iure delectus tenetur, eos praesentium, illum deleniti ullam blanditiis adipisci.</div>
        </template>

        <!-- ================================================================ -->
        <!-- Board-B PANEL  -->
        <!-- ================================================================ -->
        <template #tab-head-b>
            <span class="uppercase">Tab-B</span>
        </template>
        <template #tab-panel-b>
            <div class="text-xl mb-4 capitalize">Tab-b</div>
            <div>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam consequuntur cumque perferendis
                molestiae optio consectetur quis illo voluptatem voluptatibus, ut odio expedita reiciendis blanditiis
                provident laudantium animi qui velit soluta maiores sed ducimus omnis. Reprehenderit tempore voluptate
                quo velit optio iure delectus tenetur, eos praesentium, illum deleniti ullam blanditiis adipisci.</div>
        </template>

        <!-- ================================================================ -->
        <!-- Board-C PANEL  -->
        <!-- ================================================================ -->
        <template #tab-head-c>
            <span class="uppercase">Tab-C</span>
        </template>
        <template #tab-panel-c>
            <div class="text-xl mb-4 capitalize">Tab-c</div>
            <div>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam consequuntur cumque perferendis
                molestiae optio consectetur quis illo voluptatem voluptatibus, ut odio expedita reiciendis blanditiis
                provident laudantium animi qui velit soluta maiores sed ducimus omnis. Reprehenderit tempore voluptate
                quo velit optio iure delectus tenetur, eos praesentium, illum deleniti ullam blanditiis adipisci.</div>
        </template>

        <!-- ================================================================ -->
        <!-- Board-D PANEL  -->
        <!-- ================================================================ -->
        <template #tab-head-d>
            <span class="uppercase">Tab-D</span>
        </template>
        <template #tab-panel-d>
            <div class="text-xl mb-4 capitalize">Tab-d</div>
            <div>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam consequuntur cumque perferendis
                molestiae optio consectetur quis illo voluptatem voluptatibus, ut odio expedita reiciendis blanditiis
                provident laudantium animi qui velit soluta maiores sed ducimus omnis. Reprehenderit tempore voluptate
                quo velit optio iure delectus tenetur, eos praesentium, illum deleniti ullam blanditiis adipisci.</div>
        </template>

        <!-- ================================================================ -->
        <!-- Board-E PANEL  -->
        <!-- ================================================================ -->
        <template #tab-head-e>
            <span class="uppercase">Tab-E</span>
        </template>
        <template #tab-panel-e>
            <div class="text-xl mb-4 capitalize">Tab-e</div>
            <div>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam consequuntur cumque perferendis
                molestiae optio consectetur quis illo voluptatem voluptatibus, ut odio expedita reiciendis blanditiis
                provident laudantium animi qui velit soluta maiores sed ducimus omnis. Reprehenderit tempore voluptate
                quo velit optio iure delectus tenetur, eos praesentium, illum deleniti ullam blanditiis adipisci.</div>
        </template>

        <!-- ================================================================ -->
        <!-- Board-F PANEL  -->
        <!-- ================================================================ -->
        <template #tab-head-f>
            <span class="uppercase">Tab-F</span>
        </template>
        <template #tab-panel-f>
            <div class="text-xl mb-4 capitalize">Tab-f</div>
            <div>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam consequuntur cumque perferendis
                molestiae optio consectetur quis illo voluptatem voluptatibus, ut odio expedita reiciendis blanditiis
                provident laudantium animi qui velit soluta maiores sed ducimus omnis. Reprehenderit tempore voluptate
                quo velit optio iure delectus tenetur, eos praesentium, illum deleniti ullam blanditiis adipisci.</div>
        </template>

    </BraveTabs>



</template>

<script>
import { BraveTabs } from "bravevue";
export default {
    components: {
        BraveTabs
    },
}
</script>