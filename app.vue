<template>
  <div>
    <NuxtLink :to="'/'">首页</NuxtLink>
    <NuxtLink :to="'/hot'">热门</NuxtLink>
    <NuxtPage keepAlive />
  </div>
</template>
