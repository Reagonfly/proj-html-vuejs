<script>
export default {
    
}
</script>

<template lang="">
    <footer class="container-fluid">
        <div class="row">
            <div class="col-3 mt">
                <h4>Get In Touch</h4>
                <span>Have a Question for us?<br>we'll answer your problem here</span>
                
                <ul class="d-flex flex-wrap">
                    <li><a href="#"><i class="fa-brands fa-facebook"></i></a></li>
                    <li><a href="#"><i class="fa-brands fa-pinterest mx-1"></i></a></li>
                    <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
                    <li><a href="#"><i class="fa-brands fa-linkedin mx-1"></i></a></li>
                    <li><a href="#"><i class="fa-brands fa-instagram"></i></a></li>
                </ul>

            </div>
            <div class="col-2 mt">
                <h4>Support</h4>
                <ul>                    
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Online Chat</a></li>
                    <li><a href="#">Whatsapp</a></li>
                    <li><a href="#">Telegram</a></li>
                    <li><a href="#">Snapchat</a></li>
                </ul>
            </div>
            <div class="col-2 mt">
                <h4>About</h4>
                <ul>                    
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Career</a></li>
                    <li><a href="#">Job</a></li>
                    <li><a href="#">In press</a></li>                                    
                </ul>
            </div>
            <div class="col-2 mt">
                <h4>Faq</h4>
                <ul>                    
                    <li><a href="#">Account</a></li>
                    <li><a href="#">Order</a></li>
                    <li><a href="#">Delivery</a></li>
                    <li><a href="#">Payment</a></li>
                    <li><a href="#">Return</a></li>
                </ul>
            </div>
            <div class="col-3 mt">                
                <h4>Contact Me</h4>
                <div class="icon">
                    <i class="fa fa-location-arrow"></i>
                    <span>4500 Mercantile plaza,suite 300,fort worth,TX,76137,USA</span>
                </div>
                <div class="icon">
                    <i class="fa fa-phone my-3"></i>
                    <span>+1(817)901 3377</span>
                </div>
                <div class="icon">
                    <i class="fa fa-envelope"></i>
                    <span>info@example.com</span>
                </div>
            </div>
        </div>
        <hr>
        <div class="row">
            <div class="col-12">
                <div class="cr d-flex justify-content-center">
                    <h5>Copyright 2022 by AttdogMilo.com</h5>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss">
  @use '../styles/generals.scss' as *;
  @use '../styles/partials/variables.scss' as *;

  footer{
    height: 400px;
    width: 100vw;
    background-color: $myboi;
    span{
            color: $footxt;
        }

    hr{
        color: $onbltx;
        text-align: center;
    }

    .cr{
        color: $bleached;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }
    .mt{
      margin-top: 6rem;
      padding: 0 0 15px;
      font-size: 16px;
      padding: 0 2rem;

        .icon{
            i{
                margin-right: 2rem;
                color: $range;
                line-height: 30px;
                display: inline-block;
            }
        }

        h4{
            color: $range;
        }

        ul{
            list-style: none;
            padding-left: 0pt;
        
            li{
                margin-top: .5rem;
                a{
                    color: $footxt;
                    text-decoration: none;
                }
            }
        }
    }
  }
  
</style>