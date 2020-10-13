<template>
  <nav>
    <div class="nav-wrapper">
      <router-link to="/" class="brand-logo">Tasks</router-link>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <router-link tag="li" to="/" exact active-class="active"><a href="">create</a></router-link>
        <router-link tag="li" to="/list" active-class="active"><a href="">list</a></router-link>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>
