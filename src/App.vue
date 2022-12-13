<template>
    <section>
    <div class="str ind2-home">
           <Nav />
    </div>
   </section>
   <home />


    <Footer />
  <RouterView />
</template>

<script>
  import Nav from './components/layouts/Nav.vue';
  import home from './components/layouts/home.vue'
  import Footer from './components/layouts/Footer.vue';

  export default {
    name: 'App',
    components: { Footer, home, Nav },
  }
</script>


<!-- <style scoped>
    .hom-top {
        transition: all 0.5s ease;
        background: none;
        box-shadow: none;
    }

    .top-ser {
        display: none;
    }

    .dmact .top-ser {
        display: block;
    }

    .caro-home {
        margin-top: 90px;
        float: left;
        width: 100%;
    }

    .carousel-item:before {
        background: none;
    }
</style> -->
