<template>
  <div>
    <h1>Issue</h1>
    <VBtn color="primary">Button test</VBtn>
    <div class="pa-8 bg-surface-bright">
      <VSheet :height="200" :width="200">
        <VTextarea label="Textarea"></VTextarea>
      </VSheet>
    </div>
    <NuxtLink :to="{ name: 'issue-nested-issue' }">Go to nested issue</NuxtLink>
    <NuxtPage></NuxtPage>
  </div>
</template>
