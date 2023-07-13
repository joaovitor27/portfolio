<template>
  <div class="container portfolio-container">
    <div class="columns is-multiline is-variable is-6-mobile">
      <div class="column is-one-third">
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">
              <span style="margin-right: 10px">Themos Vagas</span>
              <span class="is-pulled-right">
                    <a>
                      <span class="tag is-default">v1.0.0</span>
                    </a>
                    <span class="tag is-default">Desktop</span>
                    <span class="tag is-default">Mobile</span>
                  </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="ThemosVagas" alt="Landing template screenshot">
            </figure>
            <div class="content">
              Projeto de renovação do themos vagas o canal mais famoso do piauí de vagas de emprego. O projeto ainda
              está em andamento e ainda não se encontra em produção, mas logo abaixo temos uma versão beta para
              visualização.
              Esse projeto gerido por mim como programador fullstack, onde trabalhei no back-end com Django e Django
              rest-framework, no front foi usado html, css e javascript puro, mas a intenção é migrar todas as telas
              para react ou vue.
              O css foi feito pro outro programador: <a href="https://github.com/hudsonvini" target="_blank"
                                                        rel="noopener noreferrer">@hudsonvini</a>, pois não sou tão bom
              com css 😅. O banco de dados escolhido foi o postgresql, todas as tabelas foram modeladas por mim.
              <div style="margin-top: 20px">
                <b>Última atualização:</b>
                <time datetime="2023-05-27">10:15 PM - 27 May 2023</time>
              </div>
            </div>
          </div>
          <footer class="card-footer">
            <a href="https://themosvagas.herokuapp.com/" target="_blank" rel="noopener noreferrer"
               class="card-footer-item">Preview</a>
            <a href=""
               class="card-footer-item" aria-disabled="true">Source
              Code: Privado</a>
          </footer>
        </div>
      </div>
      <div class="column is-one-third">
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">
              <span style="margin-right: 10px">API Whatsapp</span>
              <span class="is-pulled-right">
                <span class="tag is-default">v1.0.0</span>
                <span class="tag is-default">Api Rest</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="ApiWhatsapp" alt="Landing template screenshot">
            </figure>
            <div class="content">
              Projeto desenvolvido para usar em conjunto com chatbot desenvolvido em python. Essa é uma API não official
              do whatsapp para enviar mensagens, receber e replicar outras funcionalidades que o whatsapp contem através
              de uma API Rest.
              Foi desenvolvido inteiro por mim para empresa RevGás, para testarmos o bot para futuramente migrar para
              api official do Whatsapp.
              <div style="margin-top: 20px">
                <b>Última atualização:</b>
                <time datetime="2023-02-01">11:09 PM - 11 Out 2022</time>
              </div>
            </div>
          </div>
          <footer class="card-footer">
            <a class="card-footer-item" href="https://github.com/joaovitor27/project_api_whatsapp" target="_blank"
               rel="noopener noreferrer">Sem Preview</a>
            <a href="https://github.com/joaovitor27/project_api_whatsapp"
               class="card-footer-item" aria-disabled="true" target="_blank" rel="noopener noreferrer">Source
              Code</a>
          </footer>
        </div>
      </div>
      <div class="column is-one-third">
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">
              <span style="margin-right: 10px">Rastreador Front-end</span>
              <span class="is-pulled-right">
                    <a>
                      <span class="tag is-default">v1.0.0</span>
                    </a>
                    <span class="tag is-default">Desktop</span>
                    <span class="tag is-default">Mobile</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="RastreamentoWeb" alt="Landing template screenshot">
            </figure>
            <div class="content">
              Projeto pessoal com intuito de desenvolver um rastreador para colocar em meus veículos e também adquirir mais conhecimento.
              O front é feito com Vue.js onde consome uma API em python com framework FastAPI que também foi desenvolvida por mim. O projeto está em fase desenvolvimento, está parada na parte física do projeto que é o rastreador.
              <div style="margin-top: 20px">
                <b>Última atualização:</b>
                <time datetime="2023-01-30">15:36 PM - 30 Jan 2023</time>
              </div>
            </div>
          </div>
          <footer class="card-footer">
            <a href="https://rastreamento-web.vercel.app/" class="card-footer-item" target="_blank"
               rel="noopener noreferrer">Preview</a>
            <a href=""
               class="card-footer-item">Source
              Code: Privado</a>
          </footer>
        </div>
      </div>
      <div class="column is-one-third">
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">
              <span style="margin-right: 10px">Rastreador Back-end</span>
              <span class="is-pulled-right">
                <span class="tag is-default">v1.0.0</span>
                <span class="tag is-default">Api Rest</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="RastreamentoBack" alt="Landing template screenshot">
            </figure>
            <div class="content">
              Projeto pessoal com intuito de desenvolver um rastreador para colocar em meus veículos e também adquirir mais conhecimento.
              O Back é feito com python com framework FastAPI, com banco de dados postgresql. O Back é responsável por gerenciar todos os usuários e dispositivos rastreador e mandar pro front.
              O projeto está em fase desenvolvimento, está parada na parte física do projeto que é o rastreador.
              <div style="margin-top: 20px">
                <b>Última atualização:</b>
                <time datetime="2023-02-06">01:03 AM - 06 Fev 2023</time>
              </div>
            </div>
          </div>
          <footer class="card-footer">
            <a href="https://rastreamento-web.vercel.app/" class="card-footer-item" target="_blank"
               rel="noopener noreferrer">Preview</a>
            <a href=""
               class="card-footer-item">Source
              Code: Privado</a>
          </footer>
        </div>
      </div>
      <div class="column is-one-third">
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">
              <span style="margin-right: 10px">Portfólio</span>
              <span class="is-pulled-right">
                <span class="tag is-default">v1.0.0</span>
                <span class="tag is-default">Desktop</span>
                <span class="tag is-default">Mobile</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="Portfolio" alt="Landing template screenshot">
            </figure>
            <div class="content" style="margin-top: 10px">
              Projeto pessoal com intuito de apresentar meu currículo e meus projetos. O front é feito com Vue.js.
              <div style="margin-top: 20px">
                <b>Última atualização:</b>
                <time datetime="2023-07-13">12:30 PM - 13 Jul 2023</time>
              </div>
            </div>
          </div>
          <footer class="card-footer">
            <a href="https://portifolio-joaovitor27.vercel.app/" class="card-footer-item" target="_blank"
               rel="noopener noreferrer">Preview</a>
            <a href="https://github.com/joaovitor27/portifolio" target="_blank" rel="noopener noreferrer"
               class="card-footer-item">Source Code</a>
          </footer>
        </div>
      </div>
    </div>
  </div>

</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'MyProjetos',
  components: {},
  data() {
    return {
      ThemosVagas: require('@/assets/Themosvagas.png'),
      ApiWhatsapp: require('@/assets/ApiWhatsapp.png'),
      RastreamentoWeb: require('@/assets/RastreadorWeb.png'),
      RastreamentoBack: require('@/assets/RastreadorBack.png'),
      Portfolio: require('@/assets/Portfolio.png'),
    }
  },
});
</script>

<style scoped>

</style>
