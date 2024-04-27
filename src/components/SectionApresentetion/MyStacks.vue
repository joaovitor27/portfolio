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
                  <progress class="progress color-default" value="90" max="100"></progress>
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
                  <progress class="progress color-default" value="85" max="100"></progress>
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
                  <progress class="progress color-default" value="85" max="100"></progress>
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
                  <progress class="progress color-default" value="75" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>SQL</strong>
                  <br>
                  <progress class="progress color-default" value="85" max="100"></progress>
                </p>
              </div>
            </div>
          </article>
          <article class="media">
            <div class="media-content">
              <div class="content">
                <p>
                  <strong>React-Native</strong>
                  <br>
                  <progress class="progress color-default" value="70" max="100"></progress>
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
.color-default {
  background-color: #021154;
}

progress::-webkit-progress-bar {
  background-color: rgb(255, 255, 255);
  border-radius: 7px;
}

progress::-webkit-progress-value {
  background-color: #0707c2;
  border-radius: 7px;
  box-shadow: 1px 1px 5px 3px rgb(4, 31, 150);
}

progress::-moz-progress-bar {
  /* style rules */
}
</style>
