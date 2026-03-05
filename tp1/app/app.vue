<template>
  <div style="background-color: #efc2c2;">
    <img src="/assets/petite_boule30.png" alt="Logo" class="logo">
    <NuxtRouteAnnouncer />
    <NuxtPage />
    <NuxtLink  to="/bonjour" style="color: blueviolet;">Page bonjour 1</NuxtLink><br>
    <NuxtLink  to="/bonjour2" style="color: gray;">Page bonjour 2</NuxtLink><br>
    <NuxtLink  to="/posts/1" style="color: blue;">Page 1</NuxtLink><br>
    <NuxtLink  to="/posts/2" style="color: violet;">Page 2</NuxtLink>
  </div>
</template>

<style>
.logo {
  width: 100px;
  height: auto;
  margin-bottom: 20px;
}
</style>