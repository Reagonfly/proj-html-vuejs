<script>
export default {

    
}
</script>

<template lang="">
    <header>
        <div class="container-fluid contacts">
            <div class="row d-flex justify-content-around">
                <div class="col-6 d-flex flex-no-wrap">
                    <ul class="d-flex flex-wrap align-items-center cont-inf">
                        <li><a href="#"><i class="fa fa-envelope"></i></a>info@example.com</li>
                        <li><a href="#"><i class="fa-solid fa-phone"></i></a>+1(817)901 3377</li>
                    </ul>
                </div>
                <div class="col-6 d-flex justify-content-end">
                    <ul class="d-flex flex-wrap align-items-center socials">
                        <li><a href="#"><i class="fa-brands fa-facebook"></i></a></li>
                        <li><a href="#"><i class="fa-brands fa-pinterest"></i></a></li>
                        <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fa-brands fa-linkedin"></i></a></li>
                        <li><a href="#"><i class="fa-brands fa-instagram"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="container-fluid">
            <nav class="navbar navbar-expand-lg navbar-light bg-light d-flex justify-content-between">
                <div class="col-6 logos">
                    <img src='../assets/img/logo.png' alt="logo">
                </div>
                <div class="col-6 collapse navbar-collapse">
                    <ul class="navbar-nav">
                        <li class="nav-item mx-2">
                            <a href="#">Home</a>
                        </li>
                        <li class="nav-item mx-2">
                            <a href="#">About</a>
                        </li>
                        <li class="nav-item active mx-2">
                            <a href="#">Services</a>
                        </li>
                        <li class="nav-item mx-2">
                            <a href="#">Training</a>
                        </li>
                        <li class="nav-item mx-2">
                            <a href="#">Blogs</a>
                        </li>
                    </ul>
                    <button>
                        <a href="#">Get In Toch!</a>
                    </button>                    
                </div>
            </nav>
        </div>
    </header>
</template>

<style lang="scss" scoped>
    @use '../styles/generals.scss' as *;
    @use '../styles/partials/variables' as *;

    .container-fluid.contacts{
        width: 100vw;
        height: 50px;
        background-color: $mud;

        .cont-inf{
            a{
                i{
                    color: $range;
                    margin-right: 10px;
                    font-size: 18px;
                }
            }
        }
        li{
            color: $bleached;
        }
        
    }

    ul{
        list-style: none;
        height: 100%;

        li{
            margin: 0 10px;
            .nav-item {
                padding: 0 0 0 40px;
                font-size: 21px;
                font-weight: 500;
            }

            .active{
                a{
                    color: $range;
                }

            }

            a{
                text-decoration: none;
                font-weight: 500;
                color: $onbltx;
                font-size: 21px;
            }

            a:hover{
                color: $range;
            }

        }
    }

    button{
        color: #fff;
        margin: 0 0 0 42px;
        background: $range;
        padding: 12px 25px;
        border-radius: 30px;
        border: 0;
        font-size: 21px;
        font-weight: 500;
        float: right;

        a{
            text-decoration: none;
            color: $bleached;
            font-weight: 500;
        }
    }

    
</style>