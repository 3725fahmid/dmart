<template>
  <div class="Card-area">
  <div class="container">
  <h2 class='text-center'>Service</h2>
    <div class="card" style="width: 18rem;">
      <img src="/image/B.jpg" class="card-img-top" alt="A" />
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </p>
        <a class='btn' href="/">
            <span>quote</span>
                <div class="liquid">
                    </div>
        </a>
      </div>
    </div>
  </div>
</div>
</template>
<script>
export default {
  name: 'services',
  head: {
    title: 'Service page',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'dMart Service page',
      },
      {
        hid: 'keywords',
        name: 'keywords',
        content:
          'vue,vuejs,dmart,javaScript,digital marketing, javascript- servicepage',
      },
    ],
  },
}
</script>
<style>
    .Card-area{
      width: 100%;
      height: auto;
      mmargin-top:20px;
      padding:10px;
      background-color: #f4f4f4;
    }
</style>
