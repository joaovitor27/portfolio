<template>
  <div class="container portfolio-container">
    <div class="columns is-multiline is-variable is-6-mobile">
      <div class="column is-one-third">
        <div class="card my-card">
          <header class="card-header">
            <p class="card-header-title">
              <span class="margin-right-10-px">Themos Vagas</span>
              <span class="is-pulled-right">
                <span class="tag is-default full-margin">v1.0.0</span>
                <span class="tag is-default full-margin">Desktop</span>
                <span class="tag is-default full-margin">Mobile</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="ThemosVagas" alt="Landing template screenshot">
            </figure>
            <div class="content has-text-justified">
              Projeto de renovação do themos vagas o canal mais famoso do piauí de vagas de emprego. O projeto ainda
              está em andamento e ainda não se encontra em produção, mas logo abaixo temos uma versão beta para
              visualização.
              Esse projeto gerido por mim como programador fullstack, onde trabalhei no back-end com Django e Django
              rest-framework, no front foi usado html, css e javascript puro, mas a intenção é migrar todas as telas
              para react ou vue. O banco de dados escolhido foi o postgresql, todas as tabelas foram modeladas por mim.
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
        <div class="card my-card">
          <header class="card-header">
            <p class="card-header-title">
              <span class="margin-right-10-px">API Whatsapp</span>
              <span class="is-pulled-right">
                <span class="tag is-default full-margin">v1.0.0</span>
                <span class="tag is-default full-margin">Api Rest</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="ApiWhatsapp" alt="Landing template screenshot">
            </figure>
            <div class="content has-text-justified margin-top">
              Projeto desenvolvido para ser usado em conjunto com um chatbot criado em Python. Esta é uma API não
              oficial do WhatsApp para enviar mensagens, receber e replicar outras funcionalidades que o WhatsApp possui
              através de uma API REST. Foi desenvolvido inteiramente por mim para a empresa RevGás, a fim de testarmos o
              bot para futuramente migrarmos para a API oficial do WhatsApp.
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
        <div class="card my-card">
          <header class="card-header">
            <p class="card-header-title">
              <span class="margin-right-10-px">Rastreador Front-end</span>
              <span class="is-pulled-right">
                <span class="tag is-default full-margin">v1.0.0</span>
                <span class="tag is-default full-margin">Desktop</span>
                <span class="tag is-default full-margin">Mobile</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="RastreamentoWeb" alt="Landing template screenshot">
            </figure>
            <div class="content has-text-justified margin-top">
              Projeto pessoal com o intuito de desenvolver um rastreador para colocar em meus veículos e também adquirir
              mais conhecimento. O frontend é feito com Vue.js, o qual consome uma API em Python com o framework
              FastAPI, também desenvolvida por mim. O projeto está em fase de desenvolvimento e está parado na parte
              física do projeto, que é o rastreador.
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
        <div class="card my-card">
          <header class="card-header">
            <p class="card-header-title">
              <span class="margin-right-10-px">Rastreador Back-end</span>
              <span class="is-pulled-right">
                <span class="tag is-default full-margin">v1.0.0</span>
                <span class="tag is-default full-margin">Api Rest</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="RastreamentoBack" alt="Landing template screenshot">
            </figure>
            <div class="content has-text-justified margin-top">
              Projeto pessoal com o intuito de desenvolver um rastreador para colocar em meus veículos e também adquirir
              mais conhecimento. O backend é feito com Python usando o framework FastAPI, com banco de dados PostgreSQL.
              O backend é responsável por gerenciar todos os usuários e dispositivos rastreadores e enviar dados para o
              frontend. O projeto está em fase de desenvolvimento, com a parte física do rastreador ainda pendente.
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
        <div class="card my-card">
          <header class="card-header">
            <p class="card-header-title">
              <span class="margin-right-10-px">Portfólio Frot-end</span>
              <span class="is-pulled-right">
                <span class="tag is-default full-margin">v1.0.0</span>
                <span class="tag is-default full-margin">Desktop</span>
                <span class="tag is-default full-margin">Mobile</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="Portfolio" alt="Landing template screenshot">
            </figure>
            <div class="content has-text-justified margin-top" style="margin-top: 10px">
              Projeto pessoal com intuito de apresentar meu currículo e meus projetos. O front é feito com Vue.js.
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
      <div class="column is-one-third">
        <div class="card my-card">
          <header class="card-header">
            <p class="card-header-title">
              <span class="margin-right-10-px">Portfólio Back-end</span>
              <span class="is-pulled-right">
                <span class="tag is-default full-margin">v1.0.0</span>
                <span class="tag is-default full-margin">API Rest</span>
              </span>
            </p>
          </header>
          <div class="card-content">
            <figure class="image">
              <img :src="PortfolioBack" alt="Landing template screenshot">
            </figure>
            <div class="content has-text-justified margin-top">
              Projeto pessoal com o intuito de apresentar meu currículo e meus projetos. O backend é feito com Python
              usando o Django Rest Framework, com banco de dados PostgreSQL. O backend é responsável por gerenciar todos
              os dados do portfólio e enviar para o frontend.
            </div>
          </div>
          <footer class="card-footer">
            <a href="https://github.com/joaovitor27/api_portfolio" class="card-footer-item" target="_blank"
               rel="noopener noreferrer">Preview</a>
            <a href="https://github.com/joaovitor27/api_portfolio" target="_blank" rel="noopener noreferrer"
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
      ThemosVagas: require('@/assets/img/Themosvagas.png'),
      ApiWhatsapp: require('@/assets/img/ApiWhatsapp.png'),
      RastreamentoWeb: require('@/assets/img/RastreadorWeb.png'),
      RastreamentoBack: require('@/assets/img/RastreadorBack.png'),
      Portfolio: require('@/assets/img/Portfolio.png'),
      PortfolioBack: require('@/assets/img/PortfolioBack.png'),
    }
  },
});
</script>

<style scoped>
.margin-top {
  margin-top: 10px;
}

a:hover {
  background-color: #041f96;
  color: white;
}

.my-card {

}

.my-card header {
  background-color: #021154;
}

.my-card .margin-right-10-px {
  margin-right: 10px;
  color: white
}

.my-card .full-margin {
  margin: 3px;
}

</style>
