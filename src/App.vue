<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <nav class="thenav" id="thenav">
    <i @click="toggle"  :class="{'fa-solid fa-bars-staggered': !checkbar,'fa-solid fa-x': checkbar}"></i>
  <div class="logo">
  <img src="./assets/images/logo.png" alt="">
  </div>
  <div class="listt" :class="{'active': checkbar}">
   <ul class="nav nav-pills">

   <li class="nav-item">
    <a class="nav-link" href="#landing">home</a>
   </li>
   <li class="nav-item">
    <a class="nav-link" href="#services">services</a>
   </li>
   <li class="nav-item">
    <a class="nav-link" href="#aboutt">about</a>
   </li>
   <li class="nav-item">
    <a class="nav-link" href="#proto">portfolio</a>
   </li>
   <li class="nav-item">
    <a class="nav-link" href="#videos">videos</a>
   </li>
   <li class="nav-item">
    <a class="nav-link" href="#contact">contact us</a>
   </li>
   
   
   </ul>
  </div>
  <button class="btn btn-danger rounded">contact us now</button>
  </nav>
  
  <router-view/>
</template>



<script>
import {ref} from 'vue';
export default {
  components:{

  },
  setup(){
    let thebar = ref('');
    let checkbar = ref(false);

    let toggle = ()=>{
      checkbar.value = !checkbar.value;
    }

    return{thebar , checkbar , toggle}
  }
}
</script>


<style lang="scss">
@import './sass/main.scss';


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
}


.thenav{
  position: fixed;
  top: 0;
  z-index: 111;
  right: 0;
  left: 0;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: space-around;
  padding: 30px;
  width: 100%;
  background-color: #fff;
  box-shadow: 0px 0px 10px rgba(0,0,0,0.15)!important;

  .nav-pills .nav-link.active, 
  .nav-pills .show>.nav-link{
    background-color: $main;
  }

  i{
    font-size: 35px;
    cursor: pointer;
    transition: 0.5s;
    display: none;
  }
 
  .listt{
    // background-color: red;
    // display: flex;
  width: 70%;
  ul{
      display: flex;
      align-items: center;
    justify-content: center;
    width: 100%;
    // background-color: red;
    text-align: center;
      // gap: 10px;
      li{
        // margin: 0px 5px;
        a{
          font-size: 18px;
          text-decoration: none;
          color: #333;
          transition: 0.3s;
          &:hover{
            color: black;
          }
        }
      }
    }
   
  }
}

@media(max-width:850px){
  .thenav{
    i{
      display: block;
    }
    .listt{
      position: absolute;
      top: 100%;
      width: 50%;
      transition: 0.5s;
      transform: translateY(-200%);
      &.active{
        transform: translateY(0);
      }
      ul{
        padding: 10px;
      flex-direction: column;
      justify-content: center;
      text-align: center;
      background-color: #fff;
      box-shadow: 2px 5px 10px 5px rgba(0,0,0,0.15)!important;
      width: 100%;
      li{
        border-bottom: 1px solid #333;
        border-top: 1px solid #333;
        width: 100%;
        padding: 5px;
        margin: 5px;
        transition: 0.3s;
        a{
          font-size: 22px;
        }
        &:hover{
          background-color: rgba(128, 128, 128, 0.394);
        }
      }
    }
    }
    
  }
}

// nav {
//   // padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>
