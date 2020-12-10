<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <div class="Hero">
      <h1>Hey there, my name is Tresor </h1>

      <p>
        I'm a Software Engineer Effective in analyzing relevant information and guiding product cycle from conception to completion
      </p>
    </div>

    <div class="PortfolioWorks">
      <h2>My projects</h2>
    </div>
    <p class="home-links">
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Tresor Luzingamu'
  }
}
</script>

<style>

.Hero {
  padding: 5rem 1rem;
  color: whitesmoke;
  border-style: solid;
  border-style: solid;
  border-style: solid;
  border-color: #e35a17;
}

.PortfolioWorks {
  color: whitesmoke;
}

.home-links a {
  margin-right: 1rem;
}
</style>
