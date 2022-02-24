<template>
   <footer>
       <div class="child_wrap flex">
           <div class="join_us">
               <div class="btn">
                   <button>Join AroLove</button>
               </div>
               <br>
               <p>@ AroLove 2022</p>
           </div>
          <ul class="flex_col flex">
              <h3>COMPANY</h3>
              <li>About</li>
              <li>Careers</li>
              <li>Blog</li>
          </ul>
          <ul class="flex_col flex">
              <h3>CONDITIONS</h3>
              <li>Privacy</li>
              <li>Terms</li>
              <li>Community Guidelines</li>
          </ul>
          <ul class="flex_col flex">
              <h3>Contact</h3>
              <li>Privacy</li>
              <li>Terms</li>
              <li>Safety tips</li>
          </ul>
          <ul class="flex_col flex">
              <h3>Follow</h3>
              <li>Facebook</li>
              <li>Twitter</li>
              <li>Instagram</li>
          </ul>
          <div class="logo">
              <img src="@/assets/logo.svg" alt="">
          </div>
       </div>
   </footer>
</template>

<script>
export default {

}
</script>

<style style="scss" lang="scss" scoped> 
 footer{
     padding: 40px 0px;
     margin-top: 3em;
     background: #033138;
     color: rgb(218, 218, 218);
     .child_wrap{
        justify-content: space-between;
        ul{ 
            gap: 0.8rem 0px;
            li{
                list-style: none;
            }
        }
        .logo{
            width: 10%;
        }
     }
 }
</style>