<template>
  <NavBar></NavBar>
  <SectionHeader></SectionHeader>
  <SectionApresention></SectionApresention>
  <SkillsTags></SkillsTags>
  <SectionServices></SectionServices>

  <!-- Resume -->
  <section class="section" id="resume">
    <div class="section-heading">
      <h3 class="title is-2">Resume</h3>
      <h4 class="subtitle is-5">More about my past</h4>
      <a href="#" class="button is-link is-medium">
        <span class="icon">
          <i class="fas fa-file-alt"></i>
        </span>
        <span>Download My Resume</span>
      </a>
    </div>
  </section>

  <!-- Portfolio -->
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

  <section class="section" id="contact">
    <div class="container">
      <div class="section-heading">
        <h3 class="title is-2">Contact</h3>
        <h4 class="subtitle is-5">Get in touch</h4>
      </div>
      <br>

      <div class="columns">
        <div class="column is-6 is-offset-3">
          <div class="box">
            <div class="field">
              <label class="label">Name</label>
              <div class="control">
                <input class="input" type="text" placeholder="Text input">
              </div>
            </div>

            <div class="field">
              <label class="label">Email</label>
              <div class="control has-icons-left">
                <input class="input" type="email" placeholder="Email input" value="">
                <span class="icon is-small is-left">
                  <i class="fas fa-envelope"></i>
                </span>
              </div>
            </div>

            <div class="field">
              <label class="label">Message</label>
              <div class="control">
                <textarea class="textarea" placeholder="Textarea"></textarea>
              </div>
            </div>

            <div class="field is-grouped has-text-centered">
              <div class="control">
                <button class="button is-link is-large"><span class="icon">
                    <i class="fas fa-envelope"></i>
                  </span>
                  <span>Submit</span></button>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="section-heading">
      <p>
        <strong>Bulma Personal Template</strong> by <a href="https://mubaidr.js.org">Muhammad Ubaid Raza</a>. The
        source code is licensed
        <a href="http://opensource.org/licenses/mit-license.php">MIT</a>.
      </p>
    </div>
  </footer>
</template>

<script lang="ts">
import {defineComponent} from 'vue';
import NavBar from "@/components/NavBar.vue";
import SectionHeader from "@/components/SectionHeader.vue";
import SectionApresention from "@/components/SectionApresention.vue";
import SkillsTags from "@/components/SkillsTags.vue";
import SectionServices from "@/components/SectionServices.vue";

export default defineComponent({
  name: 'HomePage',
  components: {
    SectionServices,
    SkillsTags,
    SectionApresention,
    SectionHeader,
    NavBar
  }
});
</script>

<style scoped>

</style>
