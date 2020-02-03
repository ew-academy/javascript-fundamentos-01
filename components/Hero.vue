<template>
  <section class="section Hero">
    <div class="container HeroContainer">
      <h1>Fundamentos de Javascript</h1>
      <p class="subtitle">
        <i>Aprenda </i><strong>Javascript</strong> <i>de forma </i><strong>divertida</strong><i> com </i><strong>Erick Wendel</strong>
        
      </p>
 
      <StyledButton margin="50px 0px">{{ getRightText }}</StyledButton>
    </div>
  </section>
</template>

<script>
import StyledButton from './Button.vue'
import { getRightText } from '@/utils/helpers'

export default {
  name: 'Hero',
  components: { StyledButton },
  computed: {
    getRightText
  }
}
</script>

<style lang="scss" scoped>
.Hero {
  height: 100vh;
  background-image: url(../assets/banner.jpeg);
  background-size: cover;
  position: relative;

  &::before {
    content: "";
    position: absolute;
    width: 100vw;
    height: 100vh;
    top: 0px;
    left: 0px;
    background-color: rgba(0, 0, 0, 0.5);
  }
  
  > .HeroContainer {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;

    > h1 {
      color: #fff;
      font-size: 50px;
      font-weight: 700;
    }
    .subtitle {
      color: #fff;
      font-size: 30px;
      font-weight: 300;

      > strong {
        color: #fff;
      }
    }
  }
}
</style>

