<template>
<section>
    <Header/>
    <router-view/>
    <Footer/>
</section>
</template>

<script>
import Header from "../components/header"
import Footer from "../components/footer"

export default {
  components : {
    Header,
    Footer
  }
}
</script>