<template>
    <div>
    <div class="py-5 container">
      <div class="row">
        <div class="col-md-12 text-center">
          <h1 class="main-heading">About us</h1>
          <div class="underline mx-auto"></div>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. It was popularised in the 1960s
            with the release of Letraset sheets containing Lorem Ipsum passages,
            and more recently with desktop publishing software like Aldus
            PageMaker including versions of Lorem Ipsum.
          </p>
          <!-- <h2>Page visits: {{ count }}</h2> -->
        </div>
      </div>
    </div>
    </div>
</template>

<script>
// <script setup>

export default {
    name:'about',
     head: {
    title: 'About',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'dMart About page'
      },
      {
        hid: 'keywords',
        name: 'keywords',
        content: 'vue,vuejs,dmart,javaScript,digital marketing, javascript- Aboutpage'
      }
    ],
  }

  // const { data: count } = await useFetch('https://jsonplaceholder.typicode.com/todos/1')
  // console.log(count);
}
</script>
