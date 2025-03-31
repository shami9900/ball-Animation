# ball-Animation
.container {
    height: 90vh;
    width: 80vw;
    background-color: antiquewhite;
    }
.ball {
    height: 100px;
    width: 100px;
    position: absolute;
    bottom: 10%;
    left: 0;
    background-color: blueviolet;
    border-radius: 50%;
    animation:   animatex 6s ease-in 1s infinite, 
                animate-y 1s ease-out 1s infinite alternate      ;

    
}
@keyframes animatex {
     form {
        right: 0%;


     }
     to {
        left: 72%;
     }
}
@keyframes animate-y {
    form {
        bottom: 0%;

     }
     to {
        bottom:80% ;
     }
}
