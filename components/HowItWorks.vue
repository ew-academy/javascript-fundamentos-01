<template>
  <section class="section HowItWorks">
    <div class="container HowItWorksContainer">
      <StyledTitle margin="0px 0px 30px 0px">Como funciona?</StyledTitle>
      <p class="center">
        <ol>
          <li>Aulas gravadas e <strong>100% online</strong> com acesso direto ao <strong>forúm</strong> de alunos e <strong>instrutor</strong>.</li>
          <li>Aulas disponíveis por pelo menos <strong>2 anos</strong></li>
          <li>Aulas lançadas de <strong>forma gradual</strong> iniciando-se em <strong>20/02/2020.</strong></li>
          <li><strong>Todos</strong> os capítulos possuem <strong>desafios</strong> de fixação <strong>não obrigatórios</strong> para que você consiga aproveitar o melhor do seu tempo.</li>
          <li>O <strong>código fonte</strong> e conteúdo apresentado em aula é <strong>disponibilizado</strong> na plataforma a todo fim de capítulo.</li>
          <li>Não curtiu? Você tem até <strong>7 dias</strong> para pedir o reembolso.</li>
          <li><strong>Terão mais cursos?</strong> Sim, seguimos o modelo de sempre criar conteúdos <strong>baseados em opinião</strong> e <strong>feedback</strong> de nossos alunos.</li>
          <li>Temos <strong>preços especiais</strong> para empresas, entre em contato pelo <a href="mailto:comercial@erickwendel.com.br">comercial@erickwendel.com.br</a></li>
        </ol>
      </p>
          
    </div>
  </section>
</template>

<script>
import StyledTitle from "./Title";

export default {
  name: "HowItWorks",
  components: { StyledTitle }
};
</script>

<style lang="scss" scoped>
.HowItWorks {
  > .HowItWorksContainer {
    display: flex;
    flex-direction: column;
    align-items: center;

    > p {
      font-size: 20px;
      text-align: justify;
    }
    ol {
      list-style: none
    }
    p.center {
      width: 90%
    }
    li::before {
      content: "👉🏻 ";  
      margin-left: 0
      
    }
    // > p .center {
    //   font-size: 20px;
    //   text-align: inherit;
    // }
  }
}
</style>
