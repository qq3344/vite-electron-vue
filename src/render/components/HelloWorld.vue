<template>
    <h1>{{ title }}</h1>
</template>

<script setup lang="ts">
import { EVENTS } from "@common/events";
import { useIpc } from "@render/plugins/ipc";
import { ref } from "vue";

const props = defineProps({
    title: {
        type: String,
        default: "Vite + Electron & Esbuild"
    }
});

</script>

<style>
</style>