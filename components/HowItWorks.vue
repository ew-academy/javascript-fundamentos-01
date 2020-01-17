<template>
  <section class="section HowItWorks">
    <div class="container HowItWorksContainer">
      <StyledTitle margin="0px 0px 30px 0px">Como funciona?</StyledTitle>
      <p class="center">
        <ol>
          <li>Aulas <strong>100% online</strong> com acesso direto ao <strong>forúm</strong> de alunos e <strong>instrutor</strong>.</li>
          <li><strong>Todos</strong> os capítulos possuem <strong>desafios</strong> de fixação <strong>não obrigatórios</strong> para que você consiga aproveitar o melhor do seu tempo.</li>
          <li>O <strong>código fonte</strong> e conteúdo apresentado em aula é <strong>disponibilizado</strong> na plataforma.</li>
          <li>Não curtiu? Você tem até <strong>7 dias</strong> para pedir o reembolso.</li>
          <li><strong>Está animado?</strong> Temos o programa de pré-venda que te dará 30% de desconto no valor final.</li>
          <li>Quer divulgar para os amigos e <strong>ainda ganhar uma grana?</strong> Temos o programa de afiliados, onde cada aluno que você trazer, uma comissão é gerada a partir de um link 
          (<a 
            href="https://fb.com/page.erickwendel" 
            target="__blank">entre em contato</a> para saber mais).</li>
          <li><strong>Terão mais cursos?</strong> Sim, seguimos o modelo de sempre criar conteúdos <strong>baseados em opinião</strong> e <strong>feedback</strong> de nossos alunos.</li>
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
