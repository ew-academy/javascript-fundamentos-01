<template>
  <section class="section LearnChecks">
    <div class="container LearnChecksContainer">
      <StyledTitle
        color="#fff"
        margin="0px 0px 20px 0px">O que você vai aprender?</StyledTitle>
      <div class="LearnChecksContainer-list">
        <ul>
          <li> <span>😍</span> Criar um projeto do zero</li>
          <li> <span>🤖</span> Ciclo de vida do Javascript</li>
          <li> <span>💥</span> null, undefined e expressões booleanas </li>
        </ul>
        <ul>
          <li> <span>🙀</span> Variáveis, métodos, classes e funções</li>
          <li> <span>🦄</span> Estruturas de repetição</li>
          <li> <span>⚡</span> Dominar funções assíncronas</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
import StyledTitle from './Title'

export default {
  name: 'LearnChecks',
  components: { StyledTitle }
}
</script>

<style lang="scss" scoped>
.LearnChecks {
  background-color: #232323;

  > .LearnChecksContainer {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}

.LearnChecksContainer-list {
  display: flex;
  justify-content: space-between;

  @media screen and (max-width: 700px) {
    flex-wrap: wrap;
  }

  > ul {
    color: #fff;

    > li {
      display: flex;
      align-items: center;
      padding: 20px 0px;
      font-size: 25px;

      > span {
        font-size: 55px;
        margin-right: 5px;
      }
    }
  }
}
</style>
