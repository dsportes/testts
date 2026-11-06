<template>
  <div>{{ dx.subClass('roman').name + ' ' + new Date().toISOString() }}</div>
</template>

<script setup lang="ts" vapor>
import {test, dx} from '../src-fw/registry'

</script>