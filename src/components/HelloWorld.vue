<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <NavLink url="https://cli.vuejs.org" text="vue-cli documentation" />

    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <NavLink url="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" text="babel"/>
      <NavLink url="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" text="eslint"/>

    </ul>
    <h3>Essential Links</h3>
    <ul>
      <NavLink url="https://vuejs.org" text="Core Docs"/>
      <NavLink url="https://forum.vuejs.org" text="Forum"/>
      <NavLink url="https://chat.vuejs.org" text="Community Chat"/>
      <NavLink url="https://twitter.com/vuejs" text="News"/>
      <NavLink url="https://twitter.com/vuejs" text="Twitter"/>


    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <NavLink url="https://router.vuejs.org" text="vue-router" />
      <NavLink url="https://vuex.vuejs.org" text="vuex" />
      <NavLink url="https://github.com/vuejs/vue-devtools#vue-devtools" text="vue-devtools" />
      <NavLink url="https://vue-loader.vuejs.org" text="vue-loader" />
      <NavLink url="https://github.com/vuejs/awesome-vue" text="awesome-vue" />
    </ul>
  </div>
</template>

<script>
import NavLink from './NavLink.vue';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    NavLink
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
