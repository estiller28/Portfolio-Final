<template>
     <section id="hero" class="d-flex flex-column justify-content-center align-items-center">
      <div class="d-flex justify-content-center d-md-none hero-mobile">
        <img src="assets/img/mobile-hero.png" alt="">
      </div>
      <div class="hero-container" data-aos="fade-in">
        <h1>Daniel Estiller</h1>
        <p>I'm <span class="typed" data-typed-items="Laravel Developer, Web Artisan, Freelancer"></span></p>
      </div>
    </section>
</template>

<script>
export default {
    created(){
        let my_typed = document.createElement('script');
        my_typed.setAttribute('src', "assets/js/hero.js");
        document.head.appendChild(my_typed);
    }
}
</script>