<template>
  <div class="App">
    <nuxt />
  </div>
</template>

<script>
export default {};
</script>

<script id="hotmart_launcher_script">
  (function(l,a,u,n,c,h,e,r){l['HotmartLauncherObject']=c;l[c]=l[c]||function(){
  (l[c].q=l[c].q||[]).push(arguments)},l[c].l=1*new Date();h=a.createElement(u),
  e=a.getElementsByTagName(u)[0];h.async=1;h.src=n;e.parentNode.insertBefore(h,e)
  })(window,document,'script','//launcher.hotmart.com/launcher.js','hot');

  hot('account','8fd69c75-8b5e-39d1-acc8-b7be4f3c396a');
</script>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-157528209-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-157528209-1');
</script>

<style lang="sass">
html,
body
  width: 100%
  height: 100%

.App
  width: 100%
  height: 100%

.icon
  cursor: pointer
  margin: 5px
  display: inline-block
  vertical-align: middle
  background-repeat: no-repeat

.icon--twitter
  background-image: url('~assets/twitter.svg')
  background-size: 24px 19px
  width: 24px
  height: 19px

.icon--github
  background-image: url('~assets/github.svg')
  background-size: 22px
  width: 22px
  height: 22px

.icon--linkedin
  background-image: url('~assets/linkedin.svg')
  background-size: 22px
  width: 22px
  height: 22px
  padding-left: 15px

.icon--medium
  background-image: url('~assets/medium.png')
  background-size: 22px
  width: 22px
  height: 22px
  margin-left: 15px

.icon--web
  background-image: url('~assets/web.png')
  background-size: 22px
  width: 22px
  height: 22px
</style>

