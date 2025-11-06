<script setup lang="ts">
import {NLayoutFooter, NButton} from 'naive-ui';

function toGit(): void {
    window.open("https://github.com/juanfkr/north-ai");
}
</script>

<template>
    <n-layout-footer align="center">
        <n-button @click="toGit" text>
          <span class="github">Conheça o projeto</span>
        </n-button>
    </n-layout-footer>
</template>

<style scoped>
.n-layout-footer {
  padding: 24px;
}

span {
    font-size:  16px;
    font-weight: 500;
    text-decoration: underline;
}
</style>