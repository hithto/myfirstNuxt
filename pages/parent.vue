<template>
    <div>
      // 共用 Sidebar
      <div class="sidebar">
        <NuxtLink to="/parent/child-a">child-a</NuxtLink>
        <NuxtLink to="/parent/child-b">child-b</NuxtLink>
      </div>
      // 用來顯示子頁面內容
      <NuxtPage />
    </div>
  </template>