<script>
export default {
    
}
</script>

<template lang="">
    <main>
        <section class="midsection">
            <div class="container">
                <div class="row">
                    <div class="content">
                        <h2><strong>Welcome to</strong> DogMilo <strong>Pets</strong></h2>
                        <p>Lorem Ipsum is simply dummy text of the printing <br>and typesetting industry</p>
                        <button>
                            <a href="#">Get Started</a>
                        </button>
                        
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<style lang="scss" scoped>
    @use '../styles/generals.scss' as *;
    @use '../styles/partials/variables' as *;

    .midsection{
        background-position: top;
        padding: 120px 0;
        background-size: cover;
        background-repeat: no-repeat;
        background-image: url('../assets/img/b.png');
    }
    .content{

        img{
            width: 5%;
            padding: 10px;
            background: #70d0f7;
            border-radius: 5px;
        }

        h2{
            font-size: 46px;
            color: $bleached;
        }
        p{
            padding: 14px 0;
            font-size: 20px;
            color: $bleached;
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
            transition: 0.5s;
    
            a{
                text-decoration: none;
                color: $bleached;
                font-weight: 500;
            }
        }
        button:hover{
            color: $bleached;
            background-color: $navy;
            a:hover{
                color: $bleached;
            }
        }
    }

</style>