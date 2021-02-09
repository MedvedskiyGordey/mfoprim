<template>
  <div>
    <Header/>
    <BlockOne/>
    <News/>
    <Company/>
    <TeleMail/>
    <Map/>
    <Footer/>
  </div>
</template>

<script>
  import Header from "@/components/Header";
  import Footer from "@/components/Footer";
  import Footer from "@/components/BlockOne";
  import Footer from "@/components/News";
  import Footer from "@/components/Company";
  import Footer from "@/components/TeleMail";
  import Footer from "@/components/Map";
  export default {
    name: "MainLayout",
    components: {
      Header, Footer, BlockOne, News, Company, TeleMail, Map
    }
  }
</script>

<style scoped>

</style>