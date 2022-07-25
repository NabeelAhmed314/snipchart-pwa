<template>
  <div class="main">
    <Header/>
    <nuxt/>
    <Footer/>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script
      id="snipcart"
      src="https://cdn.snipcart.com/themes/v3.2.1/default/snipcart.js"
      data-api-key="YTQ5MmQzN2QtOTViMC00Mjk0LThlMGQtNmNhMmJhYmU3YmQ5NjM3OTQzMzE5OTQ2MzY3MDk3"
    ></script>
  </div>
</template>

<script>
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Header,
    Footer
  }
};
</script>
