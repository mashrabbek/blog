<template>
  <v-app dark>
    <Header />
    <Container />
    <Footer />
  </v-app>
</template>
<script>
import Header from "./header";
import Footer from "./footer";
import Container from "./container";

export default {
  components: {
    Header,
    Footer,
    Container
  },
  data() {
    return {};
  }
};
</script>
