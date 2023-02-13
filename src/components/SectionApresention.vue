<template>
  <section class="section" id="about">
    <div class="section-heading">
      <h3 class="title is-2">Sobre mim</h3>
      <h4 class="subtitle is-5">João Vitor, "rei da programação"</h4>
      <div class="container">
        <p>Eu sou desemvolvedor web a <strong>4 anos</strong>, e durante esses anos vim adquirindo cada vez mais
          experiencia como programador,
          gosto mais de trabalhar na parte do back end, mas já fiz alguns trabalho com frontend como esse portfólio.
          Atualmente
          estou cursando
          <strong>ciência da computação</strong>, no 6º período e sou estagiário na startup Revgás como <strong>desemvolvedor
            back-end</strong>.
        </p>
      </div>
    </div>

    <div class="columns has-same-height is-gapless">
      <div class="column">
        <div class="card">
          <div class="card-content">
            <h3 class="title is-4">Perfil</h3>

            <div class="content">
              <table class="table-profile">
                <tr>
                  <th colspan="1"></th>
                  <th colspan="2"></th>
                </tr>
                <tr>
                  <td>Endereço:</td>
                  <td>Rua Quinze, Nº 5628, Santa Maria</td>
                </tr>
                <tr>
                  <td>Telefone:</td>
                  <td>(86) 9 9588-0950</td>
                </tr>
                <tr>
                  <td>Email:</td>
                  <td>joaovitor.monteiro.188@gmail.com</td>
                </tr>
              </table>
            </div>
            <br>
            <div class="buttons has-addons is-centered">
              <a href="https://github.com/joaovitor27" class="button is-dark">Github</a>
              <a href="https://www.linkedin.com/in/jo%C3%A3o-vitor-monteiro-577a49196/"
                 class="button is-dark">LinkedIn</a>
              <a href="https://twitter.com/Joao__Vitor27" class="button is-dark">Twitter</a>
            </div>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img
                  src="../../public/img/desenvolvedor-front-end.webp"
                  alt="Placeholder image">
            </figure>
          </div>
        </div>
      </div>
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
                      <progress class="progress is-info" value="75" max="100"></progress>
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
                      <progress class="progress is-info" value="70" max="100"></progress>
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
    </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'SectionApresention',
  components: {}
});
</script>


<style scoped>

</style>
