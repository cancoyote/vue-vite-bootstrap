<script setup>
import Header from '../components/AppHeader.vue';
import Sidebar from '../components/AppSidebar.vue';
import Popover from '../components/AppPopover.vue';
import Guides from '../components/AppGuides.vue';
import Footer from '../components/AppFooter.vue';
</script>

<template>
  <div class="container py-1 px-0 mx-auto">
    <Header />
    <Sidebar />
    <Popover />
    <Guides />
    <Footer />
  </div>
</template>
