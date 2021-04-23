<template>
  <Header />
  <Navigation />
  <Slider />
  <Main />
  <Footer />
</template>

<script>
import Header from "@/components/Header";
import Navigation from "@/components/Navigation";
import Slider from "@/components/Slider";
import Footer from "@/components/Footer";
import Main from "@/components/Main";

export default {
  components: {
    Header,
    Navigation,
    Slider,
    Footer,
    Main,
  },
};
</script>
