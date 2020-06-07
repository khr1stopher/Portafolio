<template>
	<nav class="navbar" role="navigation" aria-label="main navigation" style="background: transparent;">
        <div class="container is-widescreen">
            <div class="navbar-brand">
                <router-link to="/" class="navbar-item" style="color: #02fcf7;">
                    Khristopher Pineda
                </router-link>
                <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                </a>
            </div>
            <div class="navbar-end">
                <router-link to="/about" class="navbar-item" >
                    About
                </router-link>
                <router-link to="/Experience" class="navbar-item" >
                    Experience
                </router-link>
                <router-link to="/Work" class="navbar-item" >
                    Work
                </router-link>
                <router-link to="/Contact" class="navbar-item" >
                    Contact
                </router-link>
                <div class="buttons">
                    <b-button type="" outlined style="background: transparent;border-color: #ec0113;color: #ec0113;">Curriculum</b-button>
                </div>
            </div>
        </div>
    </nav>
</template>
<script>
export default {
  name: 'barra',
  props: {
  }
}
</script>
<style>
.navbar-end router-link{
	color: #02fcf7 !important;
}
</style>