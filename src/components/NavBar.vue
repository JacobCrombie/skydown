<template>
  <b-navbar toggleable="lg" type="warning" variant="dark">
    <b-navbar-brand to="/">Skydown Skydiving</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav> </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item to="/"> Home </b-nav-item>
        <b-nav-item to="/tandem">Tandem</b-nav-item>
        <b-nav-item to="/experienced">Experienced</b-nav-item>
        <b-nav-item to="/about">About</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>


<script>
export default {
  name: "nav-bar",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {},
};
</script>

<style lang="scss" scoped>
</style>