<template>
    <div>
        <div class="footer-dec">
    <img src="../assets/images/footer-dec.png" alt="">
  </div>

      <div class="thefooterr">
      
       <div class="w-100">
       <div class="row justify-content-between gap-5" style="width: 90%; margin:20px auto">
         <div class="col-xl-2 col-lg-2 col-md-3">
           <div class="box d-flex flex-column gap-3 align-items-center">
            <div class="logo">
             <img src="../assets/images/logo.png" alt="">
            </div>
            <p class="muted">khaledsawada1@gmail.com</p>
            <div class="iconss">
                <i class="fa-brands fa-facebook"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-youtube"></i>
                <i class="fa-brands fa-twitter"></i>
            </div>
           </div>
         </div>
         <div class="col-xl-2 col-lg-2 col-md-3">
           <div class="box d-flex flex-column align-items-center">
            <div class="box d-flex flex-column align-items-center">
               <h3 class="fw-bolder fs-4 text-dark">services</h3>
               <div class="linkss d-flex flex-column gap-3 text-center ">
                <span class="text-muted">SEO Development</span>
                <span class="text-muted">Business Growth</span>
                <span class="text-muted">Social Media Managment</span>
                <span class="text-muted">Website Optimization</span>
               </div>
            </div>
           </div>
         </div>
         <div class="col-xl-2 col-lg-2 col-md-3">
           <div class="box d-flex  flex-column align-items-center">
            <div class="box d-flex flex-column align-items-center">
               <h3 class="fw-bolder fs-4 text-dark">Community</h3>
               <div class="linkss d-flex flex-column gap-3">
                <span class="text-muted">Digital Marketing</span>
                <span class="text-muted">Business Ideas</span>
                <span class="text-muted">Website Checkup</span>
                <span class="text-muted">Page Speed Test</span>
               </div>
            </div>
           </div>
         </div>
         <div class="col-xl-2 col-lg-2 col-md-3">
           <div class="box d-flex flex-column align-items-center">
             <h3 class="fs-4 fw-bolder text-dark">Subscribe Newsletters</h3>
             <p class="text-muted">Get our latest news and ideas to your inbox</p>
             <div class="theinput">
              <input type="text" placeholder="your email...">
              <i class="fa-solid fa-paper-plane"></i>
             </div>
           </div>
         </div>
       </div>
       </div>
       <hr>
       <h3 class="text-center">created by <span>khaled sawada</span></h3>
      </div>
    </div>
</template>

<script >

</script>

<style lang="scss">
@import '../sass/main.scss';
.footer-dec {
  width: 100%;
  height: 200px;
  img{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  margin-top: 100px;
}

.thefooterr{
    // background-color: #3333332c;
    padding: 20px;
    margin: 0px;
    width: 100%;
    .box{
        .iconss{
            display: flex;
            align-items: center;
            gap: 20px;
            i{
                background-color: $second;
                padding: 10px;
                border-radius: 50%;
                color: #fff;
                cursor: pointer;
            }
        }
        .theinput{
            display: flex;
            align-items: center;
            background-color: $second;
            padding: 10px;
            border-radius: 20px;
            i{
                color: #fff;
            }
            input{
                border: none;
                background-color: transparent;
                outline: none;
                color: #fff;
            }
        }
    }
}



</style>