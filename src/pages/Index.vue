<template>
  <Layout>
    <div class="container">
      <div class="hero">
        <h1 class="hero-title">Simplicity. Aesthetics. Value.</h1>
        <h2 class="hero-subtitle">
          Hi there, I'm an independent Digital Designer &amp; Art Director
          focused on digital design for brands that like to have fun.
        </h2>
      </div>
      <div class="projects">
        <div class="project">
          <g-link to="/" class="project-link">
            <g-image
              alt="Nichlas W. Andersen"
              src="../../static/1.jpg"
              class="thumbnail"
            />
          </g-link>
          <h3 class="project-title">Banana</h3>
          <div class="categories">
            <span class="category">photography </span>
            <span class="category">pink</span>
          </div>
        </div>
        <div class="project">
          <g-link to="/" class="project-link">
            <g-image
              alt="Nichlas W. Andersen"
              src="../../static/2.jpg"
              class="thumbnail"
            />
          </g-link>
          <h3 class="project-title">Pineapple</h3>
          <div class="categories">
            <span class="category">photography </span>
            <span class="category">blue</span>
          </div>
        </div>
        <div class="project">
          <g-link to="/" class="project-link">
            <g-image
              alt="Nichlas W. Andersen"
              src="../../static/3.jpg"
              class="thumbnail"
            />
          </g-link>
          <h3 class="project-title">Ice Cream</h3>
          <div class="categories">
            <span class="category">photography </span>
            <span class="category">yellow</span>
          </div>
        </div>
        <div class="project">
          <g-link to="/" class="project-link">
            <g-image
              alt="Nichlas W. Andersen"
              src="../../static/4.jpg"
              class="thumbnail"
            />
          </g-link>
          <h3 class="project-title">Porta400</h3>
          <div class="categories">
            <span class="category">photography </span>
            <span class="category">yellow</span>
          </div>
        </div>
      </div>
    </div>

    <div>
      <div class="latest-journals-heading container">
        <span class="label">Latest and greatest</span>
      </div>
      <div class="latest-journals">
        <div class="container">
          <g-link to="/" class="journal">
            <h3 class="journal-title">Gridsome with Forestry CMS</h3>
          </g-link>
          <g-link to="/" class="journal">
            <h3 class="journal-title">VueJS for your next project</h3>
          </g-link>
          <g-link to="/" class="journal">
            <h3 class="journal-title">macOS development environment</h3>
          </g-link>
          <g-link to="/" class="journal">
            <h3 class="journal-title">About Typography</h3>
          </g-link>
        </div>
      </div>
    </div>
    <footer class="footer">
      <div class="container">
        <span>Copyright © 2021</span>
      </div>
    </footer>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

