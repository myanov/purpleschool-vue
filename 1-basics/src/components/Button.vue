<script setup></script>

<template>
  <button class="button">
    <slot></slot>
  </button>
</template>

<style scoped>
  .button {
    font-family: var(--font);
    font-weight: 400;
    font-size: 24px;
    line-height: 36px;
    letter-spacing: 0%;
    min-width: 335px;
    box-sizing: border-box;
    padding: 16px 10px;
    border-radius: 100px;
    color: var(--color-btn);
    background: var(--color-bg-btn);
    border: none;
    outline: none;
    cursor: pointer;
  }

  .button:hover {
    background: var(--color-bg-btn-hover);
  }
</style>
