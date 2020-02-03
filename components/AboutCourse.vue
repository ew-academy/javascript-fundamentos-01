<template>
  <section class="section AboutCourse">
    <div class="container AboutCourseContainer">
      <StyledTitle margin="0px 0px 30px 0px">Sobre o curso</StyledTitle>
      <p>
        Para você que está com <strong>dificuldades</strong> para <strong>aprender a programar</strong>, <strong>fazendo faculdade</strong>, tem curiosidade em aprender Javascript ou deseja aprender a sua primeira linguagem de programação na <strong>prática</strong>, sem lero lero, encontrou o treinamento que estava procurando!.
      </p>
      <br>
      <p>
        Este treinamento foi criado junto à <strong>comunidade</strong> brasileira de Javascript e Node.js, a partir de uma pesquisa sobre o que <strong>mais necessitavam</strong>, suas principais <strong>dificuldades</strong> e <strong>desafios</strong>. 
      </p>
      <br>
      <p>
        Você aprenderá desde o <strong>básico de Javascript</strong>, ciclo de vida, variáveis, tipos de dados, manipulação de listas à uma <strong>aplicação real</strong>. Ao fim do curso você receberá um belíssimo <strong>certificado</strong> e terá <strong>acesso direto ao instrutor</strong> via nosso grupo oficial no Facebook.

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
