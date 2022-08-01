<template>
  <b-navbar>
    <template slot="brand">
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <strong>ModGenerator</strong>
      </b-navbar-item>
    </template>
    <template slot="start">
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <b-icon icon="home"></b-icon>
        <span>Home</span>
      </b-navbar-item>
      <b-navbar-item tag="router-link" :to="{ name: 'Modules' }">
        <b-icon icon="playlist-plus"></b-icon>
        <span>Modules</span>
      </b-navbar-item>
    </template>
    <template slot="end">
      <b-navbar-item tag="div">
        <div class="buttons">
          <a class="button is-primary" target="_blank" href="https://github.com/k7brasil/ModuleGenerator">
            <b-icon icon="git"></b-icon>&nbsp;
            <strong>GitHub</strong>
          </a>
        </div>
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {
  name: "Navbar"
};
</script>