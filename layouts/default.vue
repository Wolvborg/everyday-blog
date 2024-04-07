import { NuxtLink } from '#build/components';
<template>
  <div>
    <header>
      <NuxtLink to="/">Home</NuxtLink> | <NuxtLink to="/about">About</NuxtLink>
    </header>
    <slot />
    <footer>Footer</footer>
  </div>
</template>
