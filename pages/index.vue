<template>
  <!-- <Tutorial/> -->
  <div>
    <div class="main-section">
      <div class="container d-flex justify-content-between">
      <div class="m-auto">
<h1>A simple quiz app</h1>
<h2 >Select from various categories</h2>
</div>
<div>
  <img class="d-none d-md-block" src="@/assets/images/home-section.png">
</div>
</div>
    </div>
    <div>
      <div class="card" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="card-link">Card link</a>
    <a href="#" class="card-link">Another link</a>
  </div>
</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style lang="scss" scoped>
.main-section{
  background-image: url('@/assets/images/home-main.jpg');
  padding: 20px 0;
  border-radius: 0px 0px 20px 20px;
  h1{
    color: #FFF;
text-shadow: 0px 4px 4px rgba(0, 0, 255, 0.25), 0px 4px 4px rgba(0, 0, 255, 0.25);
font-family: Roboto;
font-size: 52px;
font-style: normal;
font-weight: 700;
line-height: normal;
padding-left: 10%;

  }
  h2{
    color: #FFF;
font-family: Roboto;
font-size: 20px;
font-style: normal;
font-weight: 400;
line-height: normal;
padding-left: 10%;

  }
}
</style>