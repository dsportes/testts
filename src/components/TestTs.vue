<template>
  <img alt="Vue logo" src="../assets/img/anonymous-w.svg" width="32" height="32" />
  <div class="font-title">Bonjour !</div>
  <div class="font-mono selx btn" @click="resetDh">{{ dx.subClass('roman').name + ' ' + dhs }}</div>
</template>

<script setup lang="ts" vapor>
import {test, dx} from '../src-fw/registry'
import { ref, type Ref, computed } from 'vue'

const dh: Ref<number> = ref(0)
const dhs: Ref<string> = computed(() => new Date(dh.value).toISOString())

const resetDh = () => { dh.value = Date.now() }

resetDh()

</script>

<style lang="scss" scoped>
@use '../css/app';

</style>