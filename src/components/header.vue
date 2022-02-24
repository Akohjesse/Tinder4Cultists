<template>
   <header class="child_wrap flex">
        <div class="logo">
           <img src="@/assets/logo.svg" alt="">
        </div>
        <nav>
            <ul class="flex">
                <li>Testimonials</li>
                <li>Aro</li>
                <li>Bucanner</li>
                <li>BlackAxe</li>
                <li>Login</li>
            </ul>
        </nav>
        <div class="btn login">
            <button>Sign up</button>
        </div>
        
   </header>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
header {
  justify-content: space-between;
  align-items: center;
  padding: 20px 0px;
  .logo {
    width: 6%;
    img {
      width: 100%;
    }
  }
  nav {
    width: 50%;
    ul {
      justify-content: space-evenly;
      li {
        list-style: none;
        font-size: 1.1em;
      }
    }
  }
  .login {
    button {
      background: rgb(255, 230, 0);
    }
  }
  a {
    text-decoration: none;
    color: inherit;
  }
}

</style>