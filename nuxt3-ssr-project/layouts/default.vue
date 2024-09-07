<template>
    <div>
        <Header />
        <div class="full-screen-minus-160 bg-white w-11/12 mt-2 m-auto p-1.5">
            <slot />
        </div>
        <Footer />
    </div>
</template>
<script setup lang="ts">
import Header from "./Header.vue";
import Footer from "./Footer.vue";

</script>
<style>
.full-screen-minus-160 {
  height: calc(100vh - 180px);
}
</style>