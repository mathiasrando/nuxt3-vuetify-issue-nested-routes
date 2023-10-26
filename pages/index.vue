<template>
  <div>
    <h1>Index</h1>
    <div class="pa-8 bg-surface-bright">
      <VSheet :height="200" :width="200">
        <VTextarea label="Textarea"></VTextarea>
      </VSheet>
    </div>
    <NuxtLink :to="{ name: 'issue' }">Go to issue</NuxtLink>
  </div>
</template>
