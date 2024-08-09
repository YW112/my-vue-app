<script setup>
  import myheader from './components/myheader.vue';
  import mystore from './components/mystore.vue';
  import mybasket from './components/mybasket.vue';
  import myfilter from './components/myfilter.vue';
  import myfalsestore from './components/myfalsestore.vue';
  const props = defineProps ({
    title: String,
    price: Number,
    isAdded: Boolean
})
</script>

<template>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Prata&display=swap" rel="stylesheet">
<div class="wrapper w-4/5 m-auto h-screen rounded-xl shadow-xl mt-14">
  <myheader></myheader>
  <main>
    <myfilter></myfilter>
    <div class="products-list">
      <mystore></mystore>
      <mystore></mystore>
      <myfalsestore></myfalsestore>
      <br>
      <mystore></mystore>
      <mystore></mystore>
      <mystore></mystore>
      <mystore></mystore>
      <mystore></mystore>
      <mystore></mystore>
    </div>
  </main>
</div>
</template>

<style>
body {
  background-color: rgba(255, 255, 255, 1);
  display: flexbox;
  margin: 0;
}
.bask-prod {
  border: 1px solid blue;
  color: black;
}
main {
  display: flexbox;
  flex-direction: row;
  flex-wrap: wrap;
  width: clamp (360px, 100%, 1920px);
}
.products-list {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
</style>
