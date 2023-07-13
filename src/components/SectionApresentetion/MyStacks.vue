<template>
  <div class="column">
    <div class="card">
      <div class="card-content skills-content">
        <h3 class="title is-4">Skills</h3>
        <div class="content">

          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>Python:</strong>
                  <br>
                  <progress class="progress is-info" value="90" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>Django:</strong>
                  <br>
                  <progress class="progress is-info" value="85" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>API Rest:</strong>
                  <br>
                  <progress class="progress is-info" value="85" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>TypeScript</strong>
                  <br>
                  <progress class="progress is-info" value="75" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>Databases</strong>
                  <br>
                  <progress class="progress is-info" value="85" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>Vue</strong>
                  <br>
                  <progress class="progress is-info" value="50" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'MyStacks',
  components: {}
});
</script>

<style scoped>

</style>
