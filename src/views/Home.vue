<template>
  <div class="home">
    <Header />
    <Hero />
    <Product />
    <Gallery />
    <Partner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import Product from "@/components/Product.vue";
import Gallery from "@/components/Gallery.vue";
import Partner from "@/components/Partner.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    Product,
    Gallery,
    Partner,
    Footer,
  },
};
</script>
