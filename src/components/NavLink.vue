<script>
  export default {
    name: "NavLink",
    props: ['url', 'text']
  }
</script>

<template>
  <li>
    <a :href="url" rel="noopener"  target="_blank">{{ text }}</a>
  </li>
</template>

<style>
  a {
    text-decoration: none;
    color: purple;
    font-size: 2rem;
  }
</style>
