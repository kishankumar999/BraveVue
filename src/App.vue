<template>
    <!-- Sidebar -->
    <div class="fixed top-0 bottom-0 left-0 bg-zinc-100 dark:bg-zinc-900 h-screen w-60 p-4 overflow-auto">
        <!-- Sidebar Component -->
        <SideBar></SideBar>
    </div>

    <!-- Preview Panel -->
    <div
        class="fixed top-0 left-60 h-screen w-[calc(100vw_-_240px)] bg-white dark:bg-zinc-800 px-7 py-7 dark:text-white overflow-auto">
        <router-view />
    </div>
</template>

<script>
import SideBar from './components/sidebar-panel.vue';
export default {
    components: {
        SideBar
    }
}
</script>
