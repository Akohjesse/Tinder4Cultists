<template>
  <div class="home">
     <Header/>
     <main class="child_wrap flex">
       <div class="txt_copy flex flex_col">
         <h1>Date a Cultist Near You today 💚💛🖤</h1>
         <p>By clicking Join, you agree to our Terms. Learn how we process your data in our Privacy Policy and Cookies Policy.</p>
         <div class="btn">
           <button>Join Our Waitlist</button>
         </div>
       </div>
       <div class="hero_img img">
         <img src="@/assets/vegan.png" alt="">
       </div>
     </main>
     <Footer/>
  </div>
</template>

<script>
import Header from '../components/header.vue'
import Footer from '../components/footer.vue'
export default {
  components: {
    Header, Footer
  },
};
</script>


<style lang="scss" src="../scss/home.scss">
</style>
