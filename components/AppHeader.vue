<template>
  <header>
    <h1>Bad dad jokes</h1>
     <div><nuxt-link to="/">Home</nuxt-link>
       <nuxt-link to="/jokes">Jokes</nuxt-link>
      <nuxt-link to="/about">About</nuxt-link>
      </div>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
header {
    width: 100vw;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #254436;
    height: 15vh;
    position: fixed;
    top: 0;
}

header div {
  padding: 0 2rem;
}

h1 {
   color: #f0f0f0;
   padding-left: 2rem;
}

a {
  margin-left: .5rem;
  color: #f0f0f0;
}

</style>