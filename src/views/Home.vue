<template>
  <div class="home">
     <Header/>
     <main class="child_wrap flex">
       <div class="txt_copy">
         <h1>Who Dey Breathe??</h1>
         <p>Date a Cultist Near You today</p>
         <p>By clicking Join, you agree to our Terms. Learn how we process your data in our Privacy Policy and Cookies Policy.</p>
         <div class="btn">
           <button>Join Our Waitlist</button>
         </div>
       </div>
       <div class="hero_img img">
         <img src="@/assets/axe.png" alt="">
       </div>
     </main>
  </div>
</template>

<script>
import Header from '../components/header.vue'
export default {
  components: {
    Header
  },
};
</script>


<style lang="scss" src="../scss/home.scss">
</style>
