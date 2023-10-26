<script lang="ts" setup></script>

<template>
  <VApp>
    <VNavigationDrawer elevation="3" permanent rail rail-width="84">
      <VList nav>
        <VListItem class="navigation__link mb-2 py-2" :to="{ name: 'index' }">
          <VIcon>mdi-plus</VIcon>
          <div class="navigation__text mt-2">Index</div>
        </VListItem>
        <VListItem class="navigation__link mb-2 py-2" :to="{ name: 'issue' }">
          <VIcon>mdi-plus</VIcon>
          <div class="navigation__text mt-2">Issue</div>
        </VListItem>
        <VListItem
          class="navigation__link mb-2 py-2"
          :to="{ name: 'issue-nested-issue' }"
        >
          <VIcon>mdi-plus</VIcon>
          <div class="navigation__text mt-2">Nested issue</div>
        </VListItem>
        <VListItem
          class="navigation__link mb-2 py-2"
          :to="{ name: 'issue-nested-issue-grandchild' }"
        >
          <VIcon>mdi-plus</VIcon>
          <div class="navigation__text mt-2">grandchild</div>
        </VListItem>
      </VList>
    </VNavigationDrawer>
    <VMain>
      <slot />
    </VMain>
  </VApp>
</template>

<style lang="scss" scoped></style>
