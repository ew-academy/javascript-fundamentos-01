<template>
  <section class="section VideoPublicity">
    <div class="container VideoPublicityContainer">
      <iframe  
        class="iframe"
        src="https://www.youtube.com/embed/qFCE1lSeZrM" 
        frameborder="0" 
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen/>
    </div>
  </section>
</template>

<script>
import StyledTitle from './Title';

export default {
  name: 'VideoPublicity',
  components: { StyledTitle },
};
</script>

<style lang="scss" scoped>
.iframe {
        width: 900px;
        height: 500px;
      }
.VideoPublicity {
  background-color: #232323;

  > .VideoPublicityContainer {
    display: flex;
    flex-direction: column;
    align-items: center;

    > div {
      display: flex;
      flex-wrap: wrap;
      flex-direction: row;
      align-items: center;

      @media screen and (max-width: 700px) {
        flex-direction: column;
      }

      > a {
        @media screen and (max-width: 700px) {
          margin-top: 20px;
        }

        > img {
          display: inline-block;
          vertical-align: middle;
          max-width: 90%;
          width: 200px;
          height: auto;
          margin: 0 12px 20px 12px;
        }
      }
      
    }
  }
}
</style>

