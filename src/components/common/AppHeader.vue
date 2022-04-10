<template>
  <header>
    <router-link to="/">
      <img src="@/assets/img/logo.svg" alt="logo" class="logo" />
    </router-link>
    <nav class="nav__list">
      <router-link to="/korean">한식</router-link>
      <router-link to="/western">양식</router-link>
      <router-link to="/japanese">일식</router-link>
      <router-link to="/chinese">중식</router-link>
      <router-link to="/baking">제과·제빵</router-link>
      <router-link to="/baking">바리스타</router-link>
      <router-link to="/event">이벤트</router-link>
      <router-link to="/customer">고객센터</router-link>
    </nav>
    <div class="nav__icons">
      <router-link to="/cart"><i class="uil uil-shopping-bag"></i></router-link>
      <router-link to="/login"><i class="uil uil-user"></i></router-link>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style></style>
