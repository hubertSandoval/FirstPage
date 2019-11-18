<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width-device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie-edge">
    <title>Redes</title>
    <link rel="icon" type="image.png" href="images/css.png">
    <link href="https://fonts.googleapis.com/css?family=Fjalla+One|Source+Sans+Pro:400i&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/redes.css"/>
    <style type="text/css">
      /*
COLORES
azul oscuro-oscuro       #0d1627
azul oscuro              #14223c
azul claro               #0cc3fb
azul footer              #09111d
azul gradiente           #16719e
azul botones             #10a5d9
color linkedin           #0678b6
color youtube            #e83f3a
color instagram          #d0315d
color google             #e83f3a
color facebook           #4b69b0
color twitter            #37b1e1
color snapchat           #ffe100
color pinterest          #e83f3a
color whstsapp           #2ba63a



*/



body {
    margin: 0;
}

h1 {
    color: white;
}

p {
    color: white;
}




/*seccionesheader*/










.header {
    /* height: 50px;                         while get the content */
    /* border: solid red 2px; */
    background-color: #0d1627;
    display: flex;
    justify-content: space-between;
    /* position: sticky;
    top: 0;
    z-index: 5; */
}


    .header-image {
        padding-inline-start: 20px;
        padding-top: 2px;
    }

        .header-image-img {
            height: 45px;
            padding: 5px 0;
        }

    .header-nav {
        /* border: solid white 1px; */
        height: 45px;
        /* width: ; */
        padding-right: 20px;
        padding-top: 5px;
        display: flex;
        justify-content: space-evenly;
    }

        .hero-a {
            /* border: solid red 1px; */
            margin: 0 20px;
            text-decoration: none;
            color: white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            /* background-color: blueviolet; */
            background-image: url(../images/fondo-a.png);
            height: 20px;
            transition-duration: 0.2s;
            background-position-x: -5px;
        }

        .hero-a:hover {
            background-position-x: 10px;
        }

        .redes-a {
            /* border: solid red 1px; */
            margin: 0 20px;text-decoration: none;
            color: white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-image: url(../images/fondo-b.png);
            height: 20px;
            transition-duration: 0.2s;
            background-position-x: -5px;
        }

        .redes-a:hover {
            background-position-x: 10px;
        }


        .bolas-a {
            /* border: solid red 1px; */
            margin: 0 20px;text-decoration: none;
            color: white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-image: url(../images/fondo-c.png);
            height: 20px;
            transition-duration: 0.2s;
            background-position-x: -5px;
        }

        .bolas-a:hover {
            background-position-x: 10px;
        }

        .footer-a {
            /* border: solid red 1px; */
            margin: 0 20px;text-decoration: none;
            color: white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-image: url(../images/fondo-d.png);
            height: 20px;
            transition-duration: 0.2s;

        }

        .footer-a:hover {
            background-position-x: 10px;
        }



    .codepen-a {
            /* border: solid red 1px; */
            margin: 0 20px;text-decoration: none;
            color: white;
            padding: 5px 15px;
            /* height: 10px; */
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-color: #0cc3fb;
            border-radius: 50px;
            transition-duration: 0.05s;
        }

        .codepen-a:hover {
            background-color: #16719e;
        }

/*seccioneshero*/







.container-hero {
    display: flex;
    padding: 0;
    margin: 0 auto;
    justify-content: space-between;
}
/* align-items: center;    este va arriba en el enterior*/


.hero {
    height: auto;
    width: auto;                        /*while get the content */
    /* border: solid black 2px; */
    background-color: #14223c;
    display: flex;
    padding: 0;
    margin: 0 auto;
    justify-content: space-between;
    position: relative;
    z-index: 1;
}

    .h1-hero {
        font-size: 2.5rem;
        font-style: italic;

    }

    .p-hero {
        margin-bottom: 3em;
    }

    .hero-text {
        font-family: 'Calibri', 'Trebuchet MS', sans-serif;
        height: auto;                     /*while*/
        width: 50%;
        /* border: solid pink 2px; */
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding-left: 1.5rem;
        font-size: 1.2rem;
        font-weight: lighter;
        line-height: 1.5rem;
    }


        .p-hero-a {
            /* border: solid white 1px; */
            height: 60px;
            width: 150px;
            display: flex;
            justify-content: center;
            align-items: center;

        }

        .hero-text-a {
            text-decoration: none;
            /* border: solid black 1px; */
            display: inline-block;
            text-align: center;
            justify-content: center;
            color: black;
            width: 140px;
            height: 30px;
            border-radius: 30px;
            padding: 8px 0 2px 0 ;
            /* background-image: url(../images/redes.jpg); */
            /* background-size: 50px 50px; */
                 background-color: #10a5d9;
                 transition: 0.1s;
                -moz-transition: 0.1s;
                -webkit-transition:0.1s;
                /*-webkit-animation-name: botonhero; /* Safari 4.0 - 8.0 */
                /*-webkit-animation-duration: 0.1s; /* Safari 4.0 - 8.0 */
               /* animation-name: botonhero;*/
               /* animation-duration: 1s; */
                /* animation: linear; */
                /*animation-iteration-count: 1;
                animation-fill-mode: both; */
                /* animation-play-state: paused; */
        }

        .hero-text-a:hover {
            /* animation-play-state: running; */
            background-color: #16719e;
            text-decoration: none;
            /* border: solid black 1px; */
            display: inline-block;
            /* text-align:; */
            /* padding-bottom: 0.2rem; */
            justify-content: center;
            color: white;
            transition: 0.1s;
            -moz-transition: 0.1s;
            -webkit-transition: 0.1s;
            width: 145px;
            height: 33px;

        }

        /* .hero-text-a:not(:hover) {
            animation-play-state: paused;

        } */

        /* @keyframes botonhero {
            from {background-color: #10a5d9;}
            to {background-color: #16719e;}
        } */

    .hero-img {
        padding: 0;
        display: flex;
        justify-content: flex-end;
    }

        .hero-img-img {
            height: auto;
            width: auto;

        }



        /*seccionesredes*/










.redes-section {
    height: 550px;                        /*while get the content */
    /* border: solid blue 2px; */
    background-image: linear-gradient(125deg, white/*#14223c*/,white 50% ,white/*#14223c*/);
    display: flex;
    justify-content: space-between;
    padding: 0;
    border: 0;
}

.redes-left {
background-image: linear-gradient(270deg, #0cc3fb, #16719e);
/* background-image: linear-gradient(90deg, gray, white); */
/* border: solid red 1px; */
width: 33%;
display: flex;
flex-direction: column;
padding: 2rem;
/* padding-right: 1rem; */
justify-content: space-around;
position: relative;
z-index: 1;
}

    .redes-left-linkedin {
        /* border: solid black 1px; */
        /* transform: perspective(500px) rotateY(15deg); */
        height: 100px;
        /* width: 100%; */
        border-radius: 10px;
        background-image: url(https://content.linkedin.com/content/dam/business/talent-solutions/global/en_us/blog/2015/03/linkedinintroduction_teampic.jpg);
        background-size: 420px auto;
        background-repeat: no-repeat;
        background-position-y: -100px;
        display: flex;
        justify-content: flex-start;
        overflow: hidden;
        box-shadow: -10px 10px 15px 0px rgba(0, 0, 0, 0.3);

        transform: perspective(500px) rotateY(-15deg);
        -webkit-animation-name: example; /* Safari 4.0 - 8.0 */
        -webkit-animation-duration: 2s; /* Safari 4.0 - 8.0 */
        animation-name: example;
        animation-duration: 2s;
        transition: 0.3s;
        -moz-transition: 0.3s;
        -webkit-transition: 0.3s;
        /* animation: linear; */
        /* animation-iteration-count: 1; */
        /* animation-play-state: paused; */

    }

        .redes-left-linkedin:hover {
            /* animation-play-state: running; */
            transform: perspective(500px) rotateY(15deg);
            transition: 1s;
            -moz-transition: 1s;
            -webkit-transition: 1s;

        }

    /* @keyframes example {
        0% {transform: perspective(500px) rotateY(15deg);}
        20% {transform: perspective(500px) rotateY(-15deg);}
        40% {transform: perspective(500px) rotateY(15deg);}


        /* 60% {transform: perspective(500px) rotateY(15deg);} */
        /* 80% {transform: perspective(500px) rotateY(-15deg);} */
        /* 100% {transform: perspective(500px) rotateY(15deg);} */
    /* } */

        .redes-left-linkedin-tapa {
            background-color: #0678b6;
            width: 50px;
            /* border: solid red 1px; */
        }


        .redes-left-linkedin-tapa-a {
            /* border: solid black 2px; */
            background-image: url(../images/linkedinicon.png);
            /* border: solid black 1px; */
            text-align: center;
            justify-content: center;
            width: 73px;
            height: 73px;
            position: absolute;
            z-index: 3;
            top: 64px;
            left: 27px;
            margin-top: 13.5px;
            margin-left: 12px;

        }

    .redes-left-youtube {
        /* border: solid black 1px; */
        height: 100px;
        transform: perspective(500px) rotateY(15deg);
        border-radius: 10px;
        background-image: url(https://static1.abc.es/media/tecnologia/2018/07/19/yotubers-awards-jksha-kbPH--620x349@abc.png);
        background-size: 420px auto;
        background-repeat: no-repeat;
        background-position-y: -67px;
        background-position-x: -7px;
        display: flex;
        justify-content: flex-end;
        overflow: hidden;
        box-shadow: 10px 10px 15px 0px rgba(0, 0, 0, 0.3);


        transform: perspective(500px) rotateY(15deg);
        -webkit-animation-name: example1; /* Safari 4.0 - 8.0 */
        -webkit-animation-duration: 2s; /* Safari 4.0 - 8.0 */
        animation-name: example1;
        /* animation-duration: 2s;
        animation-iteration-count: 1;
        animation-play-state: paused; */
        animation-duration: 2s;
        transition: 0.3s;
        -moz-transition: 0.3s;
        -webkit-transition: 0.3s;


    }

    .redes-left-youtube:hover {
        /* animation-play-state: running; */
        transform: perspective(500px) rotateY(-15deg);
            transition: 1s;
            -moz-transition: 1s;
            -webkit-transition: 1s;
    }

    /* @keyframes example1 {
        0% {transform: perspective(500px) rotateY(-15deg);}
        25% {transform: perspective(500px) rotateY(15deg);}
        50% {transform: perspective(500px) rotateY(-15deg);} */
        /* 75% {transform: perspective(500px) rotateY(-15deg);} */
        /* 100% {transform: perspective(500px) rotateY(15deg);} */
    /* } */



        .redes-left-youtube-tapa {
            background-color: #e83f3a;
            width: 50px;
        }


            .redes-left-youtube-tapa-a {
            /* border: solid black 2px; */
            background-image: url(../images/youtubeicon.png);
            /* border: solid black 1px; */
            text-align: center;
            justify-content: center;
            width: 73px;
            height: 73px;
            position: absolute;
            z-index: 3;
            top: 137px;
            right: 40px;
            margin-top: 100px;
            margin-left: 12px;

        }


    .redes-left-instagram {
        /* border: solid black 1px; */
        transform: perspective(500px) rotateY(-15deg);
        height: 100px;
        border-radius: 10px;
        background-image: url(https://ksassets.timeincuk.net/wp/uploads/sites/54/2018/09/Team_Instagram.jpg);
        background-size: 420px auto;
        background-repeat: no-repeat;
        background-position-y: -60px;
        background-position-x: 45px;
        box-shadow: -10px 10px 15px 0px rgba(0, 0, 0, 0.3);

        display: flex;
        justify-content: space-between;
        overflow: hidden;

        transform: perspective(500px) rotateY(-15deg);
        -webkit-animation-name: example2; /* Safari 4.0 - 8.0 */
        -webkit-animation-duration: 2s; /* Safari 4.0 - 8.0 */
        animation-name: example2;
        animation-iteration-count: 1;
        animation-play-state: paused;
        animation-duration: 1s;
        transition: 0.3s;
        -moz-transition: 0.3s;
        -webkit-transition: 0.3s;


    }

    .redes-left-instagram:hover {
        /* animation-play-state: running; */
        transform: perspective(500px) rotateY(15deg);
        /* height: 130px; */
        /* filter: blur(1.5px); */
            transition: 1s;
            -moz-transition: 1s;
            -webkit-transition: 1s;
    }

    /* @keyframes example2 {
        0% {transform: perspective(500px) rotateY(15deg);}
        25% {transform: perspective(500px) rotateY(-15deg);}
        50% {transform: perspective(500px) rotateY(15deg);} */
        /* 75% {transform: perspective(500px) rotateY(15deg);} */
        /* 100% {transform: perspective(500px) rotateY(-15deg);} */
    /* } */


    .redes-left-instagram-tapa {
        background-color: #d0315d;
        width: 50px;
    }

    /* .redes-left-instagram-h1 {
        border: solid red 1px;
        text-decoration: none;
        display: flex;
        justify-content: center;
        position: absolute;
        z-index: 5;
        font-size: 2.3rem;
        left: 180px;
        top: 385px;
        width: 290px;
        border-radius: 13px;
        background-color: rgba(0, 0, 0, 0.5);
    } */


        .redes-left-instagram-tapa-a {
        /* border: solid black 2px; */
        background-image: url(../images/instagramicon.png);
        /* border: solid black 1px; */
        text-align: center;
        justify-content: center;
        width: 73px;
        height: 73px;
        position: absolute;
            z-index: 3;
            top: 64px;
            left: 27px;
            margin-top: 336px;
            margin-left: 12px;

    }







/*redes right*/





.redes-right {
background-image: linear-gradient(270deg, #16719e,  #0cc3fb);
/* background-image: linear-gradient(to right, 0,0,0,0.5); */
/* transform: rotate(6deg); */
/* border: solid green 1px; */
width: 69%;
display: flex;
flex-wrap: wrap;
justify-content: space-evenly;
align-items: center;
/* background-color: blanchedalmond; */
}




    .redes-right-google {
        background-repeat: no-repeat;
        background-size: 450px;
        background-position-x: -10px;
        background-position-y: -95px;
        background-image: url(https://regeneracion.mx/wp-content/uploads/2018/08/google-chrome.jpg);
        border-radius: 10px;
        /* border: solid lightgray 2px; */
        /* border: solid gray 1px; */
        /* width: 100px; */
        height: 100px;
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        overflow: hidden;
    }

        .redes-right-google-tapa {
            /* border: solid grey 1px; */
            background-color: #e83f3a;
            height: 35px;
            width: 100%;
            display: flex;
            justify-content: center;

        }


            .redes-right-google-a {
                background-image: url(../images/googleicon.png);
                position: relative;
                bottom: 35px;
                z-index: 2;
                width: 73px;
                height: 73px;
                /* border: solid red 1px; */
                transition-duration: 0.25s;
            }

            .redes-right-google-a:hover {
                background-image: url(../images/googleicon.png);
                position: relative;
                bottom: 45px;
                z-index: 2;
                width: 73px;
                height: 73px;
                /* border: solid red 1px; */
            }


    .redes-right-facebook {
        background-repeat: no-repeat;
        background-size: 350px;
        background-position-y: -70px;
        border-radius: 10px;
        background-image: url(https://images.sftcdn.net/images/t_app-cover-l,f_auto/p/37a5557e-96d0-11e6-a0ca-00163ec9f5fa/1706593813/facebook-windows-10-apps.29616.9007199266245907.65197407-cc70-4969-a3d7-ad4ed1459629.jpg);
        /* border: solid lightgray 2px; */
        /* border: solid red 1px; */
        /* width: 100px; */
        height: 100px;
        width: 30%;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        overflow: hidden;
    }

        .redes-right-facebook-tapa {
            /* border: solid grey 1px; */
            background-color: #4b69b0;
            height: 35px;
            width: 100%;
            display: flex;
            justify-content: center;

        }


        .redes-right-facebook-a {
            background-image: url(../images/facebookicon.png);
            position: relative;
            bottom: 35px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
            transition-duration: 0.25s;

        }

        .redes-right-facebook-a:hover {
            background-image: url(../images/facebookicon.png);
            position: relative;
            bottom: 45px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
        }


    .redes-right-twitter {
        background-repeat: no-repeat;
        background-size: 380px;
        background-position-x: -40px;
        background-position-y: -110px;
        border-radius: 10px;
        background-image: url(https://as.com/betech/imagenes/2019/01/22/portada/1548195940_877984_1548199609_noticia_normal.jpg);
        /* border: solid lightgray 2px; */
        /* border: solid red 1px; */
        /* width: 100px; */
        height: 100px;
        width: 30%;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        overflow: hidden;
    }

        .redes-right-twitter-tapa {
            /* border: solid grey 1px; */
            background-color:#37b1e1;
            height: 35px;
            width: 100%;
            display: flex;
            justify-content: center;

        }

            .redes-right-twitter-a {
                background-image: url(../images/twittericon.png);
                position: relative;
                bottom: 35px;
                z-index: 2;
                width: 73px;
                height: 73px;
                /* border: solid red 1px; */
                transition-duration: 0.25s;

            }


            .redes-right-twitter-a:hover {
                background-image: url(../images/twittericon.png);
                position: relative;
                bottom: 45px;
                z-index: 2;
                width: 73px;
                height: 73px;
                /* border: solid red 1px; */
            }


    .redes-right-snapchat {
        background-repeat: no-repeat;
        background-size: 520px;
        background-position-x: -80px;
        background-position-y: -110px;
        border-radius: 10px;
        background-image: url(https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2017/11/Snapchat-Redesign-796x398.jpg);
        /* border: solid lightgray 2px; */
        /* border: solid red 1px; */
        /* width: 100px; */
        height: 100px;
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        overflow: hidden;
    }

        .redes-right-snapchat-tapa {
            /* border: solid grey 1px; */
            background-color: #ffe100;
            height: 35px;
            width: 100%;
            display: flex;
            justify-content: center;
        }


        .redes-right-snapchat-a {
            background-image: url(../images/snapchaticon.png);
            position: relative;
            bottom: 35px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
            transition-duration: 0.25s;

        }


        .redes-right-snapchat-a:hover {
            background-image: url(../images/snapchaticon.png);
            position: relative;
            bottom: 45px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
        }

    .redes-right-pinterest {
        background-repeat: no-repeat;
        background-size: 450px;
        background-position-y: -55px;
        border-radius: 10px;
        background-image: url(https://newsroom.pinterest.com/sites/default/files/inline-images/2018-WebSave-screen-GTM-01.jpg);
        /* border: solid lightgray 2px; */
        /* border: solid red 1px; */
        /* width: 100px; */
        height: 100px;
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        overflow: hidden;
    }


        .redes-right-pinterest-tapa {
            /* border: solid grey 1px; */
            background-color: #e83f3a;
            height: 35px;
            width: 100%;
            display: flex;
            justify-content: center;
        }


        .redes-right-pinterest-a {
            background-image: url(../images/pinteresticon.png);
            position: relative;
            bottom: 35px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
            transition-duration: 0.25s;

        }


        .redes-right-pinterest-a:hover {
            background-image: url(../images/pinteresticon.png);
            position: relative;
            bottom: 45px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
        }


    .redes-right-whatsapp {
        background-repeat: no-repeat;
        background-size: 350px;
        background-position-x: -40px;
        background-position-y: -110px;
        border-radius: 10px;
        background-image: url(https://e.rpp-noticias.io/normal/2019/07/26/385038_821071.png);
        /* border: solid lightgray 2px; */
        /* border: solid red 1px; */
        /* width: 100px; */
        height: 100px;
        width: 30%;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        overflow: hidden;
    }

        .redes-right-whatsapp-tapa {
            /* border: solid grey 1px; */
            background-color: #2ba63a;
            height: 35px;
            width: 100%;
            display: flex;
            justify-content: center;
        }



        .redes-right-whatsapp-a {
            background-image: url(../images/whatsappicon.png);
            position: relative;
            bottom: 35px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
            transition-duration: 0.25s;

        }


        .redes-right-whatsapp-a:hover {
            background-image: url(../images/whatsappicon.png);
            position: relative;
            bottom: 45px;
            z-index: 2;
            width: 73px;
            height: 73px;
            /* border: solid red 1px; */
        }

/*seccionesbolas*/










.bolas-section {
    height: 550px;                        /*while get the content */
    /* border: solid blueviolet 2px; */
    background-color: #14223c;
    /* position: relative; */
    /* z-index: 1; */
}


    .bolas-top {
        /* border: solid blue 1px; */
        height: 33%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

        .bolas-top-center {
            /* border: solid red 1px; */
            width: 80%;
            height: 50%;
            background-color: #4285f4;
            box-sizing: border-box;
            padding-right: 25px;
            display: flex;
            justify-content: flex-end;
            align-items: center;
        }


            .bolas-top-center-c {
                /* border: solid red 1px; */
                width: 300px;
                height: 40%;
                display: inline-flex;
            }

                .bolas-top-center-c-chulo {
                    /* border: solid black 1px; */
                    box-sizing: border-box;
                    width: 50px;
                    height: 100%;
                    background-color: #285571;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    font-size: 1.5rem;
                    /* font-weight: 500; */
                    color: white;
                    text-decoration: none;
                    font-family: 'Calibri', 'Trebuchet MS', sans-serif;
                }

                    .bolas-top-center-c-chulo:hover {
                        color: #28cb41;
                    }

                .bolas-top-center-c-try {
                    /* border: solid yellow 1px; */
                    height: 100%;
                    width: 100%;
                    background-color: #1c3a4d;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    font-size: 1.5rem;
                    /* font-weight: 500; */
                    color: white;
                    font-family: 'Calibri', 'Trebuchet MS', sans-serif;
                }


    .bolas-bottom {
        /* border: solid gray 1px; */
        height: 66%;
        display: flex;

    }

    .bolas-bottom-left {
        /* border: solid black 3px; */
        width: 35%;
        display: flex;
        justify-content: space-evenly;
        align-items: flex-end;
        padding-bottom: 20px;
        padding-left: 90px;

        }


        .bolas-bottom-left-red {
            /* border: solid red 1px; */
            width: 70px;
            height: 70px;
            background-color: #ff685f;
            border-radius: 40px;
            position: relative;
            bottom: 200px;
            animation-name: rred;
            -webkit-animation-name: rred;
            animation-duration: 1s;
            -webkit-animation-duration: 1s;
            animation-iteration-count: infinite;
        }

        @keyframes rred {
          0%  {position: relative; bottom: 200px;}
          33%  {position: relative; bottom: 0px; height: 60px;}
          66%  {position: relative; bottom: 200px;}
          100%  {position: relative; bottom: 200px;}
        }

        .bolas-bottom-left-yellow {
            /* border: solid red 1px; */
            width: 70px;
            height: 70px;
            background-color: #ffbf2d;
            border-radius: 40px;
            position: relative;
            bottom: 200px;
            animation-name: yelow;
            -webkit-animation-name: yelow;
            animation-duration: 1s;
            -webkit-animation-duration: 1s;
            animation-delay: 0.3s;
            animation-iteration-count: infinite;
        }

        @keyframes yelow {
          0%  {position: relative; bottom: 200px;}
          33%  {position: relative; bottom: 0px; height: 60px;}
          66%  {position: relative; bottom: 200px;}
          100%  {position: relative; bottom: 200px;}
        }

        .bolas-bottom-left-green {
            /* border: solid red 1px; */
            width: 70px;
            height: 70px;
            background-color: #28cb41;
            border-radius: 40px;
            position: relative;
            bottom: 200px;
            animation-name: gren;
            -webkit-animation-name: gren;
            animation-duration: 1s;
            -webkit-animation-duration: 1s;
            animation-delay: 0.6s;
            animation-iteration-count: infinite;
        }

        @keyframes gren {
          0%  {position: relative; bottom: 200px;}
          33%  {position: relative; bottom: 0px; height: 57px;}
          66%  {position: relative; bottom: 200px;}
          100%  {position: relative; bottom: 200px;}
        }

    .bolas-bottom-right {
        /* border: solid red 1px; */
        width: 65%;
        display: flex;
        justify-content: center;
        align-items: center;

    }

    .bolas-bottom-right-img {
        width: 65%;
    }

.volver {
    border: solid #37b1e1 2px;
    height: 30px;
    width: 100px;
    position: relative;
    right: -1230px;
    bottom: 70px;
    z-index: 8;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 20px;
    text-decoration: none;
    animation-name: volver;
    -webkit-animation-name: volver;
    animation-duration: 2s;
    -webkit-animation-duration: 2s;
    /* animation-delay: 0.6s; */
    animation-iteration-count: infinite;
}

    @keyframes volver {
        0% {border: solid #37b1e1 2px;}    
        33% { border:solid #285571 2px;}
        66% { border:solid #37b1e1 2px;}
    }


/*seccionesfooter*/










.footer {
    height: 100%;                        /*while get the content */
    /* border: solid grey 2px; */
    background-color: #09111d;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}


    .footer-created {
        height: 100px;
        /* border: solid red 1px; */
        width: 24%;
        border-right: solid rgba(0, 0, 0, 0.2) 2px;
    }

        .footer-created-txt  {
            /* border: solid green 1px; */
            height: 40%;
            width: 100%;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }

        .footer-created-img {
            /* border: solid yellow 1px; */
            height: 60%;
            width: 100%;
            background-image: url(../images/created-img.png);
            background-size: 50%;
            background-repeat: no-repeat;
            background-position-x: 50%;
        }


    .footer-follow {
        /* border: solid red 1px; */
        width: 33%;
        height: 100px;
        display: flex;
        justify-content: ;
        align-items: center;
    }

        .footer-follow-txt {
            /* border: solid gray 1px; */
            height: 50%;
            width: 40%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            font-size: 1.2rem;
        }
        .footer-follow-google {
            /* border: solid gainsboro 1px; */
            height: 50%;
            width: 15%;
            background-image: url(../images/googleicon.png);
            background-repeat: no-repeat;
            background-position-x: 50%;
            background-position-y: 50%;
            background-size: 75%;
            filter: grayscale();
        }

            .footer-follow-google:hover {
                filter: none;
            }

        .footer-follow-linkedin {
            /* border: solid gainsboro 1px; */
            height: 50%;
            width: 15%;
            background-image: url(../images/linkedinicon.png);
            background-repeat: no-repeat;
            background-position-x: 50%;
            background-position-y: 50%;
            background-size: 75%;
            filter: grayscale();

        }

            .footer-follow-linkedin:hover {
                filter: none;
            }

        .footer-follow-twitter {
            /* border: solid gainsboro 1px; */
            height: 50%;
            width: 15%;
            background-image: url(../images/twittericon.png);
            background-repeat: no-repeat;
            background-position-x: 50%;
            background-position-y: 50%;
            background-size: 75%;
            filter: grayscale();

        }

            .footer-follow-twitter:hover {
                filter: none;
            }

        .footer-follow-facebook {
            /* border: solid gainsboro 1px; */
            height: 50%;
            width: 15%;
            background-image: url(../images/facebookicon.png);
            background-repeat: no-repeat;
            background-position-x: 50%;
            background-position-y: 50%;
            background-size: 75%;
            filter: grayscale();

        }

            .footer-follow-facebook:hover {
                filter: none;
            }

    .footer-aprendiste {
        /* border: solid red 1px; */
        margin: 0;
        width: 33%;
        height: 100px;
        border-left: solid rgba(0, 0, 0, 0.2) 2px;
    }

        .footer-aprendiste-txt {
            /* border: gold solid 1px; */
            height: 40%;
            width: 100%;
            color: white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            /* padding-left: 5px; */
            font-size: 1.1rem;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .footer-aprendiste-options {
            /* border: green solid 1px; */
            height: 60%;
            width: 100%;
            display: flex;
        }

            .footer-aprendiste-options-yes {
                /* border: indigo solid 1px; */
                height: 100%;
                width: 50%;
                display: flex;
                justify-content: center;
                align-items: center;
            }

                .footer-aprendiste-options-yes-a {
                    /* border: solid black 1px; */
                    background-color: #28cb41;
                    border-radius: 5px;
                    width: 50%;
                    height: 50%;
                    text-decoration: none;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                    font-weight: bold;
                    color: white;

                }

            .footer-aprendiste-options-no {
                /* border: blue solid 1px; */
                height: 100%;
                width: 50%;
                display: flex;
                justify-content: center;
                align-items: center;
            }

                .footer-aprendiste-options-no-a {
                    /* border: solid black 1px; */
                    background-color: #cb2828;
                    border-radius: 5px;
                    width: 50%;
                    height: 50%;
                    text-decoration: none;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                    font-weight: bold;
                    color: white;
                }
    </style>
</head>
<body>
    <header id="headerr" class="header">
        <div class="header-image">
            <img class="header-image-img" src="images/logo.png" alt="logo de la pagina">
        </div>
        <nav class="header-nav">
            <ol>
                <a href="#headerr" class="hero-a">Home</a>
                <a href="#redes-sectionn" class="redes-a">Redes</a>
                <a href="#bolas-sectionn" class="bolas-a">Muestra</a>
                <a href="#footerr" class="footer-a">Contacto</a>
                <a href="https://codepen.io/" class="codepen-a" target="_blank">My Codepen</a>
            </ol>
        </nav>
    </header>
    <section id="heroo" class="hero">
        <!-- <div class="container-hero"> -->
            <div class="hero-text">
                <h1 class="h1-hero">Simply, Cute, Efficient</h1>
                <p class="p-hero">Lorem ipsum dolor sit amet consectetur adipiscing elit hac taciti, sed accumsan tincidunt scelerisque neque non penatibus. Iaculis class per augue convallis mi at, cras purus nibh turpis arcu venenatis id, bibendum aptent enim suscipit lacus. Sagittis aenean nulla lectus eros justo eleifend eu nisl eget, torquent rutrum blandit sociis dui imperdiet nullam per, taciti aptent primis venenatis ligula est ultricies vulputate.</p>
                <div class="p-hero-a">
                    <a href="https://www.w3schools.com/html/html_responsive.asp" target="blank" class="hero-text-a">Conocer Más</a>
                </div>
            </div>
            <div class="hero-img">
                <img class="hero-img-img" src="images/hero.proyecto01.jpg"alt="Hero">
            </div>
        <!-- </div> -->
    </section>
    <section id="redes-sectionn" class="redes-section">      
            <div class="redes-left">
                <a class="redes-left-linkedin-tapa-a" href="https://www.linkedin.com/" target="blank"></a>
                <a class="redes-left-youtube-tapa-a" href="https://www.youtube.com/" target="blank"></a>
                <a class="redes-left-instagram-tapa-a" href="https://www.instagram.com/" target="blank"></a>
                <a href="https://www.linkedin.com/feed/" target="_blank">
                <div class="redes-left-linkedin">
                    <div class="redes-left-linkedin-tapa">
                    </div>
                </div>
                </a>
                <a href="https://www.youtube.com/" target="_blank">
                <div class="redes-left-youtube">
                        <div class="redes-left-youtube-tapa">
                        </div>
                </div>   
                </a>
                <a href="https://www.instagram.com/" target="_blank">
                    <div class="redes-left-instagram">
                        <div class="redes-left-instagram-tapa">
                        </div>
                    </div>
                    <!-- <h1 class="redes-left-instagram-h1">Visitar Instagram</h1> -->
                </a>
            </div>
            <div class="redes-right">
                <div class="redes-right-google">
                    <div class="redes-right-google-tapa">
                        <a target="_blank" class="redes-right-google-a" href="https://www.google.com/"></a>
                    </div>
                </div>
                <div class="redes-right-facebook">
                        <div class="redes-right-facebook-tapa">
                            <a target="_blank" class="redes-right-facebook-a" href="https://www.facebook.com/"></a>
                        </div>
                </div>
                <div class="redes-right-twitter">
                        <div class="redes-right-twitter-tapa">
                            <a target="_blank" class="redes-right-twitter-a" href="https://twitter.com/"></a>

                            </div>
                </div>
                <div class="redes-right-snapchat">
                        <div class="redes-right-snapchat-tapa">
                            <a target="_blank" class="redes-right-snapchat-a" href="https://www.snapchat.com/l/es/"></a>

                            </div>
                </div>
                <div class="redes-right-pinterest">
                        <div class="redes-right-pinterest-tapa">
                            <a target="_blank" class="redes-right-pinterest-a" href="https://co.pinterest.com/"></a>

                            </div>
                </div>
                <div class="redes-right-whatsapp">
                        <div class="redes-right-whatsapp-tapa">
                            <a target="_blank" class="redes-right-whatsapp-a" href="https://www.whatsapp.com/"></a>

                            </div>
                </div>
            </div>
    </section>
    <section id="bolas-sectionn" class="bolas-section">
       <div class="bolas-top">
            <div class="bolas-top-center">
                <div class="bolas-top-center-c">
                    <a target="_blank" href="https://www.w3schools.com/css/default.asp" class="bolas-top-center-c-chulo">►</a>
                    <div class="bolas-top-center-c-try">Try it yourself</div>
                </div>
            </div>
       </div> 
       <div class="bolas-bottom">
            <div class="bolas-bottom-left">
                <div class="bolas-bottom-left-red"></div>
                <div class="bolas-bottom-left-yellow"></div>
                <div class="bolas-bottom-left-green"></div>
            </div>
            <div class="bolas-bottom-right">
                <img class="bolas-bottom-right-img" src="images/bolasimg.png" alt="">
            </div>
        </div>
        <a href="#headerr" class="volver">Volver arriba</a> 
    </section>
    <footer id="footerr" class="footer">
        <div class="footer-created">
            <div class="footer-created-txt">Created by</div>
            <div class="footer-created-img"></div>
        </div>
        <div class="footer-follow">
            <div class="footer-follow-txt">Follow us</div>
            <a target="_blank" href="https://www.google.com/" class="footer-follow-google"></a>
            <a target="_blank" href="https://www.linkedin.com/" class="footer-follow-linkedin"></a>
            <a target="_blank" href="https://twitter.com/" class="footer-follow-twitter"></a>
            <a target="_blank" href="https://www.facebook.com/" class="footer-follow-facebook"></a>
        </div>
        <div class="footer-aprendiste">
            <div class="footer-aprendiste-txt">¿Did you learn something by creating this webpage?</div>
            <div class="footer-aprendiste-options">
                <div class="footer-aprendiste-options-yes">
                    <a target="_blank" class="footer-aprendiste-options-yes-a" href="https://image.shutterstock.com/image-vector/congratulations-typography-lettering-handwritten-vector-260nw-1049534216.jpg">YES</a>
                </div>
                <div class="footer-aprendiste-options-no">
                    <a target="_blank" class="footer-aprendiste-options-no-a" href="https://www.creativefabrica.com/wp-content/uploads/2018/03/Keep-learning.jpg">NO</a>
                </div>
            </div>
        </div>
    </footer>
    <script src="redes.js"> </script>
</body>
</html>
