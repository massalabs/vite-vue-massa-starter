<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue';
import {
    ClientFactory,
    DefaultProviderUrls,
    IAccount,
    WalletClient,
    INodeStatus,
} from '@massalabs/massa-web3';
console.log(DefaultProviderUrls.LABNET);
</script>

<template>
    <div>
        <a href="https://massa.net/" target="_blank">
            <img src="./assets/massa-logo.png" class="massa vue" alt="Massa logo" />
        </a>
    </div>
    <HelloWorld msg="Welcome to Massa" />
</template>

<style scoped>
.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
}
.logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
