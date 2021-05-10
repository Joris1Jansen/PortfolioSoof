<template>
  <header>
    <nav>
      <div class="logo">
        <h1><nuxt-link to="/">SW</nuxt-link></h1>
      </div>
    </nav>
  </header>
</template>

<script>
export default {}
</script>

<style scoped>
header {
  width: 100%;
  height: 6rem;
  background-color: #121212;
  display: flex;
  justify-content: center;
  align-items: center;
}

header a {
  text-decoration: none;
  color: #fff;
  display: inline-block;
  padding: 0.75rem 1.5rem;
  border: 1px solid transparent;
}

h1 {
  font-size: 3rem;
  text-align: center;
}

a:active,
a:hover,
a.router-link-active {
  border: 1px solid #fff;
}

.logo {
  width: 100%;
  text-align: center;
}

h1 a:hover,
h1 a:active,
h1 a.router-link-active {
  border-color: transparent;
}

header nav {
  width: 90%;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}

li {
  margin: 0 0.5rem;
  font-size: 1.5rem;
}
</style>
