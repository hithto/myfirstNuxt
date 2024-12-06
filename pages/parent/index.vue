<template>
    <div>
      <h2>Parent Content</h2>
    </div>
  </template>
  <script setup>
  navigateTo('/parent/child-a', { redirectCode: 301 });
  </script>