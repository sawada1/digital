<template>
 <div  data-bs-spy="scroll" data-bs-target="#thenav" data-bs-root-margin="0px 0px -40%" data-bs-smooth-scroll="true" class="scrollspy-example bg-body-danger p-3 rounded-2" tabindex="0">
 
 <div class="landing" id="landing">
  <swiper 
  :pagination="pagination" 
  :modules="modules"
  :autoplay="{
      delay: 2500,
      disableOnInteraction: false,
    }"
   class="mySwiper"
   
   >

   <swiper-slide>
  <div class="thetext">
   <span class="spann">welcome to our website</span>
   <h3>build <span>your website</span></h3>
   <h4>the best in <span>seo</span></h4>
   <p>Lorem, ipsum dolor sit amet consectetur 
   adipisicing elit. 
   Earum iure quaerat consequatur, dolor qui iste.</p>
   <div class="btnss">
    <button class="btn btn-primary">message us now</button>
    <div class="iconn">
      <i class="fa-solid fa-phone"></i>
      <span>01021189596</span>
    </div>
   </div>
  </div>
  </swiper-slide>
   <swiper-slide>
  <div class="thetext">
   <span class="spann">video tutorials</span>
   <h3>watch<span>our videos</span></h3>
   <h4>for your <span>projects</span></h4>
   <p>Lorem, ipsum dolor sit amet consectetur 
   adipisicing elit. 
   Earum iure quaerat consequatur, dolor qui iste.</p>
   <div class="btnss">
    <button class="btn btn-primary">message us now</button>
    <div class="iconn">
      <i class="fa-solid fa-phone"></i>
      <span>01021189596</span>
    </div>
   </div>
  </div>
  </swiper-slide>
   <swiper-slide>
  <div class="thetext">
   <span class="spann">online marketing</span>
   <h3>get the <span>best ideas</span></h3>
   <h4> for your <span>website</span></h4>
   <p>Lorem, ipsum dolor sit amet consectetur 
   adipisicing elit. 
   Earum iure quaerat consequatur, dolor qui iste.</p>
   <div class="btnss">
    <button class="btn btn-primary">message us now</button>
    <div class="iconn">
      <i class="fa-solid fa-phone"></i>
      <span>01021189596</span>
    </div>
   </div>
  </div>
  </swiper-slide>
   <swiper-slide>
  <div class="thetext">
   <span class="spann">welcome to our website</span>
   <h3>build <span>your website</span></h3>
   <h4>the best in <span>seo</span></h4>
   <p>Lorem, ipsum dolor sit amet consectetur 
   adipisicing elit. 
   Earum iure quaerat consequatur, dolor qui iste.</p>
   <div class="btnss">
    <button class="btn btn-primary">message us now</button>
    <div class="iconn">
      <i class="fa-solid fa-phone"></i>
      <span>01021189596</span>
    </div>
   </div>
  </div>
  </swiper-slide>
</swiper>
  <div class="image">
   <img src="../assets/images/banner-right-image.png" alt="">
  </div>
 </div>

 <div class="services" id="services">
  <div class="services-right-dec">
      <img src="../assets/images/services-left-dec.png" alt="">
    </div>
 <div class="textt text-center" style="text-transform: uppercase;">
  <h3 class="fw-bolder fs-2">we <span>provide</span> the best</h3>
  <h4 class="fw-bolder fs-2">services with <span>our tools</span></h4>
  <span class="lead fw-bold fs-4 text-black-50">OUR SERVICES</span>
 </div>
   <div class="container">
   <div class="mainbox">
    <swiper
    :spaceBetween="50"
    
    :breakpoints="{
      '640': {
        slidesPerView: 1,
        spaceBetween: 20,
      },
      '768': {
        slidesPerView: 2,
        spaceBetween: 40,
      },
      '1024': {
        slidesPerView: 3,
        spaceBetween: 50,
      },
    }"
    :centeredSlides="true"
    :autoplay="{
      delay: 2500,
      disableOnInteraction: false,
    }"
    
    :pagination="{
      clickable: true,
    }"
    :navigation="true"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide>
     <div class="box">
      <h3>content ideas for your next project</h3>
       <img src="../assets/images/service-icon-01.png" alt="">
       <hr>
       <p>Lorem ipsum dolor sit amet consectetur,
        adipisicing elit. Dolore, accusantium.</p>
     </div>
    </swiper-slide>
    <swiper-slide>
     <div class="box">
      <h3>content ideas for your next project</h3>
       <img src="../assets/images/service-icon-02.png" alt="">
       <hr>
       <p>Lorem ipsum dolor sit amet consectetur,
        adipisicing elit. Dolore, accusantium.</p>
     </div>
    </swiper-slide>
    <swiper-slide>
     <div class="box">
      <h3>content ideas for your next project</h3>
       <img src="../assets/images/service-icon-03.png" alt="">
       <hr>
       <p>Lorem ipsum dolor sit amet consectetur,
        adipisicing elit. Dolore, accusantium.</p>
     </div>
    </swiper-slide>
    <swiper-slide>
     <div class="box">
      <h3>content ideas for your next project</h3>
       <img src="../assets/images/service-icon-04.png" alt="">
       <hr>
       <p>Lorem ipsum dolor sit amet consectetur,
        adipisicing elit. Dolore, accusantium.</p>
     </div>
    </swiper-slide>
  </swiper>  
   </div>
   <div class="services-left-dec">
        <img src="../assets/images/services-right-dec.png" alt="">
      </div>
   </div>
 </div>
 <div class="about" id="aboutt">
 <div class="image">
  <img src="../assets/images/about-left-image.png" alt="">
 </div>
 <div class="textt" id="aboutText" >
  <h3>
    Grow Your Website With Our SEO <span>Tools</span>  & <p>Project Management</p> 
  </h3>
  <p>Lorem ipsum dolor sit amet,
   consectetur adipisicing elit.
    Asperiores, repellendus.</p>
    <div class="iconss">
     <div class="icon">
       <img src="../assets/images/service-icon-01.png" alt="">
       <h4>{{ num1 }}</h4>
       <span>seo projects</span>
       <hr>
       <p>Lorem ipsum dolor sit amet consectetur.</p>
     </div>
     <div class="icon">
       <img src="../assets/images/service-icon-02.png" alt="">
       <h4>{{num2}}</h4>
       <span>Websites</span>
       <hr>
       <p>Lorem ipsum dolor sit amet consectetur.</p>
     </div>
     <div class="icon">
       <img src="../assets/images/service-icon-03.png" alt="">
       <h4>{{num3}}</h4>
       <span>Satisfied Clients</span>
       <hr>
       <p>Lorem ipsum dolor sit amet consectetur.</p>
     </div>
    </div>
 </div>
 </div>
 <div class="projects" id="proto">
  <div class="textt text-center" style="text-transform: uppercase;">
  <h3 class="fw-bolder fs-2">Our Recent <span> projects </span> & Case</h3>
  <h4 class="fw-bolder fs-2">studies <span>For Clients</span></h4>
  <span class="lead fw-bold fs-4 text-black-50">OUR PORTFOLIO</span>
 </div>
 <div class="mainbox">
    <swiper
    :spaceBetween="50"
    
    :breakpoints="{
      '500': {
        slidesPerView: 1,
        spaceBetween: 20,
      },
      '768': {
        slidesPerView: 2,
        spaceBetween: 40,
      },
      '1200': {
        slidesPerView: 3,
        spaceBetween: 50,
      },
    }"
    :centeredSlides="true"
    :autoplay="{
      delay: 2500,
      disableOnInteraction: false,
    }"
    
    :pagination="{
      clickable: true,
    }"
    :navigation="true"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide>
     <div class="box">
<img src="../assets/images/portfolio-01.jpg" alt="">  
<div class="hover">
<div class="text">
  <h3>project1</h3>
 <p>seo & marketing</p>
</div>
</div>    
     </div>
    </swiper-slide>
    <swiper-slide>
     <div class="box">
      <img src="../assets/images/portfolio-02.jpg" alt=""> 
      <div class="hover">
<div class="text">
  <h3>project1</h3>
 <p>seo & marketing</p>
</div>
</div>       
       
     </div>
    </swiper-slide>
    <swiper-slide>
     <div class="box">
      <img src="../assets/images/portfolio-03.jpg" alt=""> 
      <div class="hover">
<div class="text">
  <h3>project1</h3>
 <p>seo & marketing</p>
</div>
</div>       
    
     </div>
    </swiper-slide>
    <swiper-slide>
     <div class="box">
      <img src="../assets/images/portfolio-04.jpg" alt=""> 
      <div class="hover">
<div class="text">
  <h3>project1</h3>
 <p>seo & marketing</p>
</div>
</div>       
     </div>
    </swiper-slide>
  </swiper>  
   </div>
 </div>

 <div class="plans">
  <div class="textt text-center" style="text-transform: uppercase;">
  <h3 class="fw-bolder fs-2">Our Recent <span> projects </span> & Case</h3>
  <h4 class="fw-bolder fs-2">studies <span>For Clients</span></h4>
  <span class="lead fw-bold fs-4 text-black-50">OUR PORTFOLIO</span>
 </div>
 <div class="container">
  <div class="row justify-content-center p-3 align-items-center gap-3">
   <div class="thecol col-xl-3 col-lg-3 col-md-5">
    <img src="../assets/images/first-plan-bg.png" alt="">
    <div class="offer">
     <h4>Starter Plan</h4>
     <span>$160</span>
     <h3>$140</h3>
     <p>10 Projects</p>
     <p>100 GB space</p>
     <p>20 SEO checkups</p>
     <p>Basic Support</p>
     <button class="btn btn-primary btn-lg">get started</button>
  </div>
   </div>
   <div class="thecol col-xl-3 col-lg-3 col-md-5">
    <img src="../assets/images/second-plan-bg.png" alt="">
    <div class="offer">
     <h4>Starter Plan</h4>
     <span>$160</span>
     <h3>$140</h3>
     <p>10 Projects</p>
     <p>100 GB space</p>
     <p>20 SEO checkups</p>
     <p>Basic Support</p>
     <button class="btn btn-primary btn-lg">get started</button>
  </div>
   </div>
   <div class="thecol col-xl-3 col-lg-3 col-md-5">
    <img src="../assets/images/third-plan-bg.png" alt="">
    <div class="offer">
     <h4>Starter Plan</h4>
     <span>$160</span>
     <h3>$140</h3>
     <p>10 Projects</p>
     <p>100 GB space</p>
     <p>20 SEO checkups</p>
     <p>Basic Support</p>
     <button class="btn btn-primary btn-lg">get started</button>
  </div>
   </div>
  
 
  </div>
 </div>
 </div>



 <div id="subscribe" class="subscribe">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="inner-content">
            <div class="row">
              <div class="col-lg-10 offset-lg-1">
                <h2>Know Your Website SEO Score by Email</h2>
                <form id="subscribe" action="" method="get">
                  <input type="text" name="website" id="website" placeholder="Your Website URL" required="">
                  <input type="text" name="email" id="email" pattern="[^ @]*@[^ @]*" placeholder="Your Email" required="">
                  <button type="submit" id="form-submit" class="main-button ">Subscribe</button>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="videos" id="videos">
  <div class="mainbox" >
    <div class="mainvideo" :class="{'active': thevideo == 1}">
    <iframe width="100%" height="100%"
     src="https://www.youtube.com/embed/JynGuQx4a1Y"
      title="YouTube video player" frameborder="0" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; 
      gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="text">
        <h4>project one</h4>
       <span>SEO &amp; Marketing</span>
      </div>
  </div>
    <div class="mainvideo" :class="{'active': thevideo == 2}">
      <iframe width="100%" height="100%" src="https://www.youtube.com/embed/RdJBSFpcO4M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

      <div class="text">
        <h4>project two</h4>
       <span>Advertising &amp; Marketing</span>
      </div>
  </div>
    <div class="mainvideo" :class="{'active': thevideo == 3}">
      <iframe width="100%" height="100%" src="https://www.youtube.com/embed/ZlfAjbQiL78" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

      <div class="text">
        <h4>project three</h4>
       <span>Digital &amp; Marketing</span>
      </div>
  </div>
    <div class="mainvideo" :class="{'active': thevideo == 4}">
      <iframe width="100%" height="100%" src="https://www.youtube.com/embed/mx1WseE7-0Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

      <div class="text">
        <h4>project four</h4>
       <span>SEO &amp; Advertising</span>
      </div>
  </div>
    <div class="projectss">
      <div @click="thevideo = 1" class="boxx">
       <h4>project one</h4>
       <span>SEO &amp; Marketing</span>
       <div class="imagee f1" :class="{'active':thevideo == 1}">
        <h3>project1</h3>
       </div>
      </div>
      <div @click="thevideo = 2" class="boxx">
       <h4>project two</h4>
       <span>Advertising & Marketing</span>
       <div class="imagee f2" :class="{'active':thevideo == 2}">
        <h3>project2</h3>
       </div>
      </div>
      <div @click="thevideo = 3" class="boxx">
       <h4>three</h4>
       <span>SEO & Marketing</span>
       <div class="imagee f3" :class="{ 'active': thevideo == 3}">
        <h3>project3</h3>
       </div>
      </div>
      <div @click="thevideo = 4" class="boxx">
       <h4>project four</h4>
       <span>SEO & Marketing</span>
       <div class="imagee f4" :class="{'active': thevideo == 4}">
        <h3>project4</h3>
       </div>
      </div>
    </div>
  </div>
  


</div>

<div id="contact" class="contact " style="position: relative;">
    <div class="container">
      <div class="row">
        <div class="col-lg-7">
          <div class="section-heading">
            <div id="map">
              <div style="width: 100%"><iframe width="100%" height="500" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=CAIRO+(My%20Business%20Name)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"><a href="https://www.maps.ie/distance-area-calculator.html">measure area map</a></iframe></div>
            </div>
            <div class="info">
              <span><i class="fa fa-phone"></i> <a href="#">01021189596<br>01021189596</a></span>
              <span><i class="fa fa-envelope"></i> <a href="#">khaledsawada1@gmail.com<br>mail@company.com</a></span>
            </div>
          </div>
        </div>
        <div class="col-lg-5 align-self-center">
          <form id="contact" action="" method="get">
            <div class="row">
              <div class="col-lg-12">
                <fieldset>
                  <input type="name" name="name" id="name" placeholder="Name" autocomplete="on" required>
                </fieldset>
              </div>
              <div class="col-lg-12">
                <fieldset>
                  <input type="surname" name="surname" id="surname" placeholder="Surname" autocomplete="on" required>
                </fieldset>
              </div>
              <div class="col-lg-12">
                <fieldset>
                  <input type="text" name="email" id="email" pattern="[^ @]*@[^ @]*" placeholder="Your Email" required="">
                </fieldset>
              </div>
              <div class="col-lg-12">
                <fieldset>
                  <input type="text" name="website" id="website" placeholder="Your Website URL" required="">
                </fieldset>
              </div>
              <div class="col-lg-12">
                <fieldset>
                  <button type="submit" id="form-submit" class="main-button">Submit Request</button>
                </fieldset>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
    <div class="contact-dec">
      <img src="../assets/images/contact-dec.png" alt="">
    </div>
    <div class="contact-left-dec">
      <img src="../assets/images/contact-left-dec.png" alt="">
    </div>
  </div>


<thefooter/>


 </div>
</template>

<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/pagination';
  import 'swiper/css/navigation';
  import { Pagination ,  Autoplay , Navigation } from 'swiper';

import {ref} from 'vue'
import thefooter from '../components/footer.vue'
export default {
  name: 'HomeView',
  components: {
    Swiper,
      SwiperSlide,
      thefooter,
  },

  setup(){
     
         let num1 = ref(0);
         let num2 = ref(0);
         let num3 = ref(0);
         let thevideo = ref(1);
    let scrolling = ()=>{
      window.addEventListener('scroll',()=>{
        let theabout = document.getElementById('aboutText');
        let pos = theabout.offsetTop;
        if(window.scrollY >= pos){
          let thecount1 = setInterval(() => {
              
              if(num1.value >= 300){
                clearInterval(thecount1);
             
              } else{
                num1.value = num1.value + 1;
              }
          },100 / 2);
          let thecount2 = setInterval(() => {
              
              if(num2.value >= 400){
                clearInterval(thecount2);
             
              } else{
                num2.value = num2.value + 1;
              }
          },100 / 2);
          let thecount3 = setInterval(() => {
              
              if(num3.value >= 300){
                clearInterval(thecount3);
             
              } else{
                num3.value = num3.value + 1;
              }
          },100 / 2);
        }
      });
    }
    scrolling();


    return {
        pagination: {
          clickable: true,
          renderBullet: function (index, className) {
            return '<span class="' + className + '">' + (index + 1) + '</span>';
          },
        },
        modules: [Pagination, Autoplay , Navigation],
        num1,
      num2,
      num3,
      thevideo
      };
    
  }

}
</script>

<style lang="scss">
@import '../sass/main.scss';
h3{
  span{
    color: $main;
  }
}
h4{
  span{
    color: $second;
  }
}
.landing{
  display: flex;
  align-items: center;
  width: 100%;
  // margin: 20px auto;
  margin-top: 90px;


  .swiper {
    width: 50%;
    height: 100%;
    position: relative;
  }

  .swiper-slide {
    position: relative;
    // text-align: center;
    // font-size: 18px;
    // background: #fff;

    // display: flex;
    // justify-content: center;
    // align-items: center;
    
  }

 
  .swiper-pagination{
    // background-color: red;
    position: absolute;
    top: 70%;
    text-align: center;
  }
  .swiper-pagination-bullet {
    width: 20px;
    height: 20px;
    text-align: center;
    // line-height: 20px;

    font-size: 14px;
    color: #000;
    opacity: 1;
    background: rgba(0, 0, 0, 0.2);
  }

  .swiper-pagination-bullet-active {
    color: #fff;
    background: $main;
  }


    .thetext{
      width: 100%;
      display: flex;
      flex-direction: column;
      background-image: url('../assets/images/baner-dec-left.png');
      background-size: cover;
      background-position: center;
      height: 600px;
      gap: 10px;
      padding: 30px;
      .spann{
        color: $main;
        font-size: 20px;
      }
      .btnss{
        display: flex;
        align-items: center;
        gap: 10px;
        button{
          font-size: 13px;
        }
        .iconn{
          display: flex;
          align-items: center;
          gap: 10px;
          i{
            color: #fff;
            background-color: $main;
            padding: 10px;
            border-radius: 50%;
          }
        }
      }
      h4,h3{
        font-size: 30px;
        font-weight: bolder;
      }
      h4{
        span{
          color: $main;
        }
       
      }
      h3{
        span { 
          color: $second;
        }
        }
    }
    .image{
      width: 70%;
      img{
        width: 100%;
      }
    }
}


.services{
  margin: 70px 0px;
  position: relative;
  .services-right-dec{
    position: absolute;
    top: 0%;
    left: 0;
    img{
      width: 300px;
    }
  }
  .services-left-dec{
    position: absolute;
    top: 70%;
    right: 0;
    img{
      width: 300px;
    }
  }
  .textt{
    h4{
      span{
        color: $main;
      }
    }
    h3{
      span{
        color: $second;
      }
    }
  }
  .mainbox{
    width: 90%;
    height: 300px;
    margin: 30px auto;
    padding: 20px;
    .box{
      height: 300px;
      text-align: center;
      display: flex;
      align-items: center;
      flex-direction: column;
      background-color: #fff;
      padding: 20px;
      h3{
        font-size: 20px;
        color: black;
        font-weight: bolder;
      }
      // box-shadow: 3px 5px 10px 3px rgba(0, 0, 0, 0.371);
      box-shadow: 0px 0px 15px rgba(0,0,0,0.05);

    }
  }
}
  .about{
    display: flex;
    align-items: center;
    gap: 10px;
    width: 90%;
    margin: 20px auto;
    .image{
      width: 50%;
      img{
        width: 100%;
      }
    }
    .textt{
      width: 50%;
      display: flex;
      align-items: center;
      flex-direction: column;
      gap: 10px;
      h3{
        font-size: 30px;
        font-weight: bolder;
        p{
          color: $main;
        }
        span{
          color: $second;
        }
      }
      .iconss{
        display: flex;
        align-items: center;
        gap: 7px;
        text-align: center;
        .icon{
          display: flex;
          flex-direction: column;
          align-items: center;
          gap: 5px;
          // text-align: center;
          span{
            color: $main;
            // margin: 5px 0px;
            font-size: 12.6px;
            font-weight: bold;
          }
          h4{
            font-size: 50px;
            font-weight: bolder;
            // margin: 5px 0px;
          }
        }
      }
    }
  }


  .projects{
    .mainbox{
      width: 95%;
      margin: 30px auto;
      // position: relative;
      overflow: visible;
      .swiper-button-prev,
      .swiper-button-next{
          background-color: $main;
          color: #fff;
          padding: 30px;
          border-radius: 30px;
          i{
            font-size: 10px;
          }
      }
      .swiper-pagination{

          .swiper-pagination-bullet{
            width: 20px;
            height: 20px;
          }

          .swiper-pagination-bullet-active{
           background-color: $main;
          }

      }
      .box{
        position: relative;
        overflow: hidden;
        transition: 0.5s;
        &:hover{
          .hover{
            transform: translateY(0);
          }
        }
        cursor: pointer;
        .hover{
          position: absolute;
          z-index: 111;
          top: 0%;
          width: 100%;
          height: 100%;
          background-color: #cccccc79;
          display: flex;
          align-items: center;
          justify-content: center;
          transition: 0.5s;
          transform: translateY(100%);
          .text{
            background-image: url('../assets/images/hover-bg.png');
            height: 200px;
            width: 300px;
            background-size: cover;
            display: flex;
            align-items: center;
            flex-direction: column;
            justify-content: center;
            color: #fff;
            transition: 0.5s;
            h3{
              font-weight: bolder;
              font-size: 25px;
            }
          }
        }
      }
    }
  }

  .subscribe {
  margin-top: 120px;
}
.subscribe .inner-content {
  background-image: url('../assets/images/subscribe-bg.png');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  border-radius: 20px;
  padding: 60px 0px;
  width: 100%;
  position: relative;
}

.subscribe .inner-content:after {
  content: '';
  background-image: url('../assets/images/subscribe-dec.png');
  position: absolute;
  width: 195px;
  height: 138px;
  background-repeat: no-repeat;
  background-position: center center;
  right: -20px;
  top: -20px;
}

.subscribe .inner-content h2 {
  font-size: 25px;
  color: #fff;
  font-weight: bolder;
  text-align: center;
  margin-bottom: 25px;
}

.subscribe .inner-content form {
  width: 100%;
  height: 80px;
  border-radius: 40px;
  background-color: #fff;
}

.subscribe .inner-content form input {
  width: 38.5%;
  margin-top: 20px;
  line-height: 40px;
  background-color: transparent;
  border: none;
  outline: none;
  padding: 0px 20px;
  font-size: 15px;
  color: #2a2a2a;
}

.subscribe .inner-content form input#website {
  border-right: 1px solid #eee;
}

.subscribe .inner-content form input::placeholder {
  color: #afafaf;
}

.subscribe .inner-content form button {
  display: inline-block;
  background-color: #03a4ed;
  font-size: 15px;
  font-weight: bold;
  color: #fff;
  width: 20%;
  margin-right: 10px;
  text-transform: capitalize;
  padding: 12px 20px;
  border-radius: 23px;
  letter-spacing: 0.25px;
  border: none;
  text-align: center;
  transition: all .3s;
}

.subscribe .inner-content form button:hover {
  background-color: #ff695f;
}

.plans{
  position: relative;

  // overflow: hidden;
  &::before{
    content: '';
    background-image: url('../assets/images/tables-left-dec.png');
    position: absolute;
    background-repeat: no-repeat;
    background-size: contain;
    height: 100%;
    width: 100%;
  }
 
  .thecol{
    z-index: 11;
    margin-top: 50px;
    position: relative;
    box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.468);
    width: 350px;
    border-radius: 20px;
    img{
      width: 100%;
        object-fit: cover;
      }
    .offer{
      position: absolute;
      top: 5%;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 3px;
     
      h3{
        font-size: 45px;
        font-weight: bolder;
        color: $main;
      }
      span{
        color: $main;
        text-decoration: line-through;
      }
      h4{
        font-size: 25px;
        font-weight: bolder;
      }
      p{
        color: grey;
      }
      button{
        transition: 0.5s;
        border: none;
        &:hover{
          background-color: $main;
         
        }
      }
    }
  }
}



.videos{
  margin-top: 100px;
  .mainbox{
    display: flex;
    align-items: center;
    width: 90%;
    margin: 50px auto;
    gap: 20px;
    height: 500px;
    .mainvideo{
      height: 100%;
     width: 70%;
     position: relative;
     transition: 0.5s;
     display: none;
     &.active{
      display: block;
     }
     .text{
      position: absolute;
      top: 0%;
      text-align: center;
      background-color: $main;
      padding: 20px;
      // border-radius: 30px;
      border-top-left-radius: 30px;
      border-bottom-right-radius: 30px;
      color: #fff;
      h4{
        font-size: 25px;
        font-weight: bolder;
      }
      span{
        font-size: 14px;
        font-weight: bold;
        
      }
     }
     iframe{
      border-radius: 30px;
     }
    }
    .projectss{
      width: 40%;
      display: flex;
      flex-direction: column;
      gap: 30px;
      .boxx{
        background-color: $main;
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding: 10px;
        border-radius: 20px;
        height: 130px;
        color: #fff;
        overflow: hidden;
        cursor: pointer;
        .imagee{
          position: absolute;
          top: 0;
          display: flex;
          align-items: start;
          justify-content: flex-start;
        
          background-repeat: no-repeat;
          background-size: cover;
          border-radius: 20px;
          width: 100%;
          height: 100%;
          transition: 0.5s;
          &.f1{  background-image: url('../assets/images/video-thumb-01.png');}
          &.f2{  background-image: url('../assets/images/video-thumb-02.png');}
          &.f3{  background-image: url('../assets/images/video-thumb-03.png');}
          &.f4{  background-image: url('../assets/images/video-thumb-04.png');}
          transform: translateY(0);      
           &.active{
            transform: translateY(-150%);
           }
          h3{
            background-color: $main;
            padding: 15px;
            border-bottom-right-radius: 20px;
            border-top-left-radius: 20px;
          }
        }
        h4{
          font-size: 25px;
           font-weight: bolder;
        }
        span{
          font-size: 14px;
          font-weight: bold;
        }
      }
    }
  }
}


@media(max-width:700px){
  .videos{
    .mainbox{
      flex-direction: column;
      height: 800px;
      .mainvideo{
        width: 100%;
      }
      .projectss{
        width: 100%;
        height: 60%;
      }
    }
  }
}


.contact {
  margin-top: 150px;
}
.contact-dec img {
  position: absolute;
  z-index: -11;
  width: 459px;
  height: 702px;
  right: 0;
  bottom: -400px;
}

.contact-left-dec img {
  position: absolute;
  z-index: -11;
  width: 174px;
  height: 319px;
  left: 0;
  top: 120px;
}

.contact-us {
  z-index: 2;
  position: relative;
  padding-top: 120px;
  margin-top: 0px;
}

.contact-us .section-heading h2 {
  margin-right: 100px;
  margin-bottom: 40px;
}

.contact-us #map iframe {
  border-radius: 23px;
  position: relative;
  z-index: 2;
}

.contact-us .info {
  margin-top: 30px;
  position: relative;
  z-index: 5;
  display: inline-flex;
}

.contact-us .info span {
  opacity: 1;
  display: inline-flex;
  margin-right: 30px;
}

.contact-us .info span i {
  float: left;
  width: 46px;
  height: 46px;
  display: inline-block;
  text-align: center;
  line-height: 46px;
  background: rgb(255,104,95);
  background: linear-gradient(105deg, rgba(255,104,95,1) 0%, rgba(255,144,104,1) 100%);
  border-radius: 50%;
  color: #fff;
  font-size: 22px;
  margin-left: 30px;
  margin-right: 15px;
}

.contact-us .info span a {
  color: #ff685f;
  font-size: 14px;
  font-weight: 400;
  line-height: 25px;
  text-transform: none;
}

form#contact {
  margin-left: -100px;
  position: relative;
  z-index: 2;
  background-image: url('../assets/images/contact-form-bg.png');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  padding: 60px 120px;
  border-radius: 20px;
}

form#contact input {
  width: 100%;
  height: 46px;
  border-radius: 0px;
  background-color: transparent;
  border-bottom: 1px solid #9bdbf8;
  border-top: none;
  border-left: none;
  border-right: none;
  outline: none;
  font-size: 15px;
  font-weight: 300;
  color: #2a2a2a;
  padding: 0px 0px;
  margin-bottom: 35px;
}

form#contact input::placeholder {
  color: #afafaf;
}

form#contact button {
  display: inline-block;
  background-color: #ff695f;
  font-size: 15px;
  font-weight: 400;
  color: #fff;
  text-transform: capitalize;
  padding: 12px 25px;
  border-radius: 23px;
  letter-spacing: 0.25px;
  border: none;
  outline: none;
  transition: all .3s;
}

form#contact button:hover {
  background-color: #03a4ed;
}




@media(max-width:540px){
  .subscribe .inner-content:after {
    z-index: -1;
  }
  .subscribe .inner-content {
    padding: 60px 30px 100px 30px;
  }
  .subscribe .inner-content form input {
    width: 49%;
  }
  .subscribe .inner-content form button {
    width: 100%;
    background-color: #ff695f;
    margin-top: 30px;
  }
}

  @media(max-width:470px){
   
    .swiper-button-prev,
      .swiper-button-next{
        display: none;
      }
   
  }

  @media(max-width:830px){
    .about{
      flex-direction: column;
      .image{
        width: 100%;
      }
      .textt{
        width: 100%;
      }
    }
  }
  @media(max-width: 850px){
    .landing{
      flex-direction: column;
      margin-top: 80px;
      .swiper{
        width: 100%;
      }
      .swiper-pagination{
    // background-color: red;
    position: absolute;
    top: 85%;
  }
      .thetext{
        width: 100%;
        height: 450px;
      }
      .image{
        width: 100%;
        background-color: #ff6a5f30;
        img{
          object-fit: contain;
          width: 100%;
        }
      }
    }
  }




  @media (max-width: 992px){
    form#contact {
    margin-left: 0px;
    margin-top: 60px;
  }
  form#contact {
    padding: 45px 30px;
  }
  }
  @media (max-width: 767px) {
    .contact-left-dec {
    display: none;
  }
  .contact-us .info {
    display: inline-block;
  }
  .contact-us .info span {
    margin-bottom: 20px;
  }
  }
</style>
