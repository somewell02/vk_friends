<template>
    <div class="app">
        <router-view/>
    </div>
</template>

<script lang="ts">
import {defineComponent} from "vue";

export default defineComponent({
    name: "App",
});
</script>

<style lang="scss" scoped>
.app {
    padding: 40px 0;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
