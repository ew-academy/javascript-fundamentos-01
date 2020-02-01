<template>
  <section class="section AboutCourse">
    <div class="container AboutCourseContainer">
      <StyledTitle margin="0px 0px 30px 0px">Sobre o curso</StyledTitle>
      <p>
        Varrendo a internet, encontramos diversos treinamentos sobre  <strong>Fundamentos</strong>  de  <strong>Javascript</strong>. Mas na maioria das vezes estes conteúdos  <strong>são focados na mesma coisa</strong>!  Este treinamento foi formatado junto à comunidade brasileira de Javascript e Node.js, mostrar os fundamentos da linguagem apresentando seus principais benefícios e tudo isso <strong>na prática</strong>.
      </p>
      <br>
      <p>
        Este treinamento foi  <strong>desenvolvido</strong>  sob medida a partir de uma pesquisa sobre o que a  <strong>comunidade brasileira mais necessitava</strong>, suas principais  <strong>dificuldades</strong>  e  <strong>desafios</strong>. Neste curso você aprenderá desde o básico de Javascript, ciclo de vida, variáveis, tipos de dados, manipulação de listas à uma aplicação real. Ao fim do curso você receberá um belíssimo certificado e terá acesso direto ao instrutor via nosso grupo oficial no facebook.
      </p>
      <br>
      <p>
        Para você que está com <strong>dificuldades</strong> em <strong>lingugagens de programação</strong>, <strong>fazendo faculdade</strong>, tem curiosidade em aprender <strong>Javascript</strong> ou deseja aprender a sua primeira linguagem de programação na prática, sem <strong>lero lero</strong>, aprendendo poder da linguagem mais popular do mundo, certamente este treinamento é para <strong>você</strong>
      </p>
     

    </div>
  </section>
</template>

<script>
import StyledTitle from "./Title";

export default {
  name: "AboutCourse",
  components: { StyledTitle }
};
</script>

<style lang="scss" scoped>

.AboutCourse {
  > .AboutCourseContainer {
    display: flex;
    flex-direction: column;
    align-items: center;

    > p {
      font-size: 20px;
      text-align: justify;
    }
    
  }
}
</style>
