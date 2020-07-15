<template>
  <Layout>
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <!-- g-image alt="Example image" src="~/favicon.png" width="135" /-->

    <h1>Tower of Code</h1>

    <p>
      A free & open source website to learn how to build websites, apps &
      anything else you desire with code.
    </p>

    <p class="home-links">
      <a
        href="https://github.com/cmok4290/tower-of-code"
        target="_blank"
        rel="noopener"
        >GitHub</a
      >
    </p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home",
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
