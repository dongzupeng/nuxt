<template>
    <div>
        <h1>我是home</h1>
        <button @click="toAbout">点击跳转到about页面</button>
    </div>
</template>

<script lang="ts" setup>
import { ref } from "vue" 
import { useRouter } from "vue-router"
const router = useRouter()
const toAbout = () => {
    router.push({ path: "/about" })
}
</script>

<style lang="scss" scoped>

</style>