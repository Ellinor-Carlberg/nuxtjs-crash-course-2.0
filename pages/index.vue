<template>
  <section>
    <div>
      <img src="../assets/man.svg" alt="a dad" />
      <h1>Welcome</h1>
      <h2>To bad dad jokes page!</h2>
    </div>
  </section>
</template>

<script>
export default {
  components: {},

  head() {
    return {
      title: "Bad dad jokes page!",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes",
        },
      ],
    };
  },
};
</script>

<style>
</style>
