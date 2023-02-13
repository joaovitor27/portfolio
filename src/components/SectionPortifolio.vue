<template>
  <section class="section" id="portfolio">
    <div class="container">
      <div class="section-heading">
        <h3 class="title is-2">Portfolio</h3>
        <h4 class="subtitle is-5">My latest works</h4>
      </div>
      <br>
      <div class="container portfolio-container">
        <div class="columns">
          <div class="column is-4">
            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span>Landing</span>
                  <span class="is-pulled-right">
                    <a href="https://github.com/jgthms/bulma/releases/tag/0.7.2">
                      <span class="tag is-default">v0.7.2</span>
                    </a>
                    <span class="tag is-default">Desktop</span>
                    <span class="tag is-default">Mobile</span>
                  </span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img src="#" alt="Landing template screenshot">
                </figure>
              </div>
              <footer class="card-footer">
                <a href="#" class="card-footer-item">Preview</a>
                <a href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/landing.html"
                   class="card-footer-item">Source
                  Code</a>
              </footer>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'SectionPortifolio',
  components: {}
});
</script>

<style scoped>

</style>
