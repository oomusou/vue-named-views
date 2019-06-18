<template>
  <div>
    <h1>About</h1>
    <router-link to="/about/us">About Us</router-link> |
    <router-link to="/about/you">About You</router-link> |
    <router-link to="/about/both">About Both</router-link>
    <router-view name="default"></router-view>
    <router-view name="another"></router-view>
  </div>
</template>
