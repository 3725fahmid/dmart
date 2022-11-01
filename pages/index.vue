<template>
      <div>
          <!-- <Slider/> -->
              <div class='py-5 container'>
                <div class="row">
                <div class="col-md-12 text-center">
                  <h1 class='main-heading'>About us</h1>
                  <div class='underline mx-auto'></div>
                  <p>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
                  </p>
                </div>
                </div>
              </div>
              <div class='p-5 bg-gray'>
                <div class='conainer'>
                  <div class='row'>
                    <div class='col-md-12 text-center'>
                       <h1 class='main-heading'>Service us</h1>
                        <div class='underline mx-auto'></div>
                    </div>
                    <div class='col-md-4 px-5'>
                      <div class='box-card '>
                        <img src='/image/B.jpg' alt='card_img' class='w-100'>
                        <div class='box-card-body'>
                          <h3 class='box-card-heading py-2'>Web designing</h3>
                          <div class='underline '></div>
                          <p>
                            There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden 
                          </p>
                        </div>
                      </div>
                    </div>

                    <div class='col-md-4 px-5'>
                      <div class='box-card'>
                        <img src='/image/A.jpg' alt='card_img' class='w-100'>
                        <div class='box-card-body'>
                          <h3 class='box-card-heading py-2'>Web devloping</h3>
                          <div class='underline '></div>
                          <p>
                            There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.
                          </p>
                        </div>
                      </div>
                    </div>

                  <div class='col-md-4 px-5'>
                      <div class='box-card'>
                        <img src='/image/D.jpg' alt='card_img' class='w-100'>
                        <div class='box-card-body'>
                          <h3 class='box-card-heading py-2'>App designing</h3>
                          <div class='underline '></div>
                          <p>
                            There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.
                          </p>
                        </div>
                      </div>
                    </div>

                  </div>
                </div>
              </div>
              <div class='py-5'>
                <div class='container'>
                <div class='row'>
                <div class='col-md-4'>
                  <h1 class='main-heading'>If you have any queryes ?</h1>
                  <h4>Pleace reach out us at contact@exam.com</h4>
                </div>
                <div class='col-md-4'>
                <nuxt-link to="/contact" class='p-2 btn btn-primary'>Contact Us</nuxt-link>
                </div>
                </div>
                </div>
              </div>
      </div>
</template>

<script>

import Slider from '../components/Slider.vue'
export default {
  name: 'IndexPage',
  components: {Slider},
   head: {
    title: 'Home page',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'dMart Home page'
      },
      {
        hid: 'keywords',
        name: 'keywords',
        content: 'vue,vuejs,dmart,javaScript,digital marketing, javascript- homepage'
      }
    ],
  }
}
</script>
