<template>
    <div class="app">
        {{ $store.state.name }}
        <router-link to="/login">登录</router-link>
        <router-link to="/main">主页</router-link>
        <router-view></router-view>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'App',
    components: {}
})
</script>

<style lang="less">
.app {
    height: 100%;
}
</style>
