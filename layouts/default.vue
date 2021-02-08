<template>
  <div class="container">
    <AppHeader />
    <nuxt/>
  </div>
</template>

<script>
import AppHeader from '../components/AppHeader'
export default {
  components: {
    AppHeader
  }
}
</script>

<style>

* {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  color: #35495e;
  margin: 0;
  padding: 0;
}

.container {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

a {
  text-decoration: none;
  font-size: 1rem;
  font-weight: 700;
  text-transform: uppercase;
  padding: .5rem;
  border: 1px solid #f0f0f0;
  border-radius: 10%;
}

h1 {
  font-size: 2rem;
}

img {
  width: 25vw;
}


/* 

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
 */

</style>
