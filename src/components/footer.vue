<template>
   <footer>
       <div class="child_wrap flex">
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
       </div>
   </footer>
</template>

<script>
export default {

}
</script>

<style style="scss" lang="scss" scoped> 
 footer{
     padding: 30px 0px;
     background: #045660;
     color: white;
     .child_wrap{
        justify-content: space-between;
        ul{ 
            gap: 0.8rem 0px;
            li{
                list-style: none;
            }
        }
     }
 }
</style>