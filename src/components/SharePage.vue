<template>

<div class="Tec">
<div class="container">

<div class="col1">
<div class="row">
    <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="price"> <div class="circle"> <i class="far fa-newspaper"></i> </div> <p> نسارع الاحداث لتصلك </p> </div> </div>

    <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="price2"> <div class="circle"> <i class="fas fa-american-sign-language-interpreting"></i> </div> <p> كل العالم بين يديك  </p> </div> </div>

    <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="price3"> <div class="circle"> <i class="fas fa-globe-americas"></i> </div>  <p> نوفر لك كل ما تبحث عنه </p> </div> </div>

    <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="price4"> <div class="circle"> <i class="fas fa-people-carry"></i> </div> <p> كل ما هو جديد من اخبار </p> </div> </div>
</div>
</div>


<div class="col2">
<div class="row">
<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="front"> 
        
<div class="circle"> <i class="fas fa-handshake"></i> </div> 
<p>نتفق او نختلف انت اولا</p>
</div> </div>

<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="front2">
<div class="circle">  <i class="fas fa-home"></i> </div>  
<p> نصلك في اي مكان </p>
 </div> </div>

<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="front3"> 
<div class="circle"> <i class="fas fa-laugh-beam"></i> </div>  
<p>نسعي لارضائكم</p> 
</div> </div>

<div class="col-lg-3 col-md-6 col-sm-12 col-xs-12"> <div class="front4"> 
<div class="circle"> <i class="fas fa-comments-dollar"></i> </div>  
<p> اسعارنا في متناولك </p>
</div> </div>
</div>
</div>

</div>
</div>



</template>


<script>
export default {
    name : "TecPage",
    props : ["doc", "ddoc", "whats", "wh", "fac", "fsub", "cash", "csub", "man", "msub", "car", "carsub"]
}
</script>

<style lang="scss" scoped>





.price, .price2, .price3, .price4{
    position: relative;
    padding: 200px 0 0 0;
    width: 90%;
     box-shadow: 2px 5px 5px 2px rgba(0, 0, 0, .5);
   

}

.price{
    background-color: #f15048 ;
}

.price p{
      font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 90px;
    color: white;
}

.price2{
    background-color: #0b1e3a ;
    
}

.price2 p{
    font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 90px;
    color: white;
}

.price3{
    background-color: #5cb85c ;
}

.price3 p{

      font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 90px;
    color: white;
    
}

.price4{
    background-color: #fb9056 ;
}

.price4 p{
      font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 90px;
    color: white;
}


.circle{
    height: 70px;
    width: 70px;
    border-radius: 50%;
    border: 10px solid white;
     position: absolute;
    top: 10%;
    left: 50%;
    transform: translate(-50%, -10%);
}

.fa-newspaper, .fa-american-sign-language-interpreting, .fa-globe-americas, .fa-people-carry{
    color: white;
    font-size: 30px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.front, .front2, .front3, .front4{
    background-color: white;
    padding: 200px 0 0 0;
    width: 80%;
    box-shadow: 2px 5px 5px 2px rgba(0, 0, 0, .5);
    position: relative;
}


.front .circle{
    height: 70px;
    width: 70px;
    border-radius: 50%;
    border: 10px solid #f15048;
     position: absolute;
    left: 50%;
    transform: translateX(-50%);

}

.front p{
       font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 80px;
    color: #f15048;
}


.fa-handshake{
    color: #f15048;

    
}

.front2 .circle{

     height: 70px;
    width: 70px;
    border-radius: 50%;
    border: 10px solid #0b1e3a;
     position: absolute;
    left: 50%;
    transform: translateX(-50%);
   

}

.front2 p{
       font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 80px;
    color: #0b1e3a;
}

.fa-home{
    color: #0b1e3a;
}

 .front3 .circle{

      height: 70px;
    width: 70px;
    border-radius: 50%;
    border: 10px solid #5cb85c;
     position: absolute;
    left: 50%;
    transform: translateX(-50%);


}


.front3 p{
       font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 80px;
    color: #5cb85c;
}

.fa-laugh-beam{
    color: #5cb85c;
}

 .front4 .circle{

    height: 70px;
    width: 70px;
    border-radius: 50%;
    border: 10px solid #fb9056;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);


}

.front4 p{
       font-size: 20px;
    font-weight: bold;
    position: relative;
    bottom: 80px;
    color: #fb9056;
}

.fa-comments-dollar{
    color: #fb9056;
}

.fa-handshake, .fa-home,  .fa-laugh-beam, .fa-comments-dollar{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 30px;
        }

@media (min-width:1024px) {

.col2{
     position: relative;
     top: -90px;
     right: 35px; 
   
}


.Tec{

      padding-top: 300px;
      padding-bottom:70px;

}


.price2, .front2{
    position: relative;
    top: 120px;
}

.price3, .front3{
    position: relative;
    top: -120px;
}



    
}


@media (max-width:1023px) {

.front{
        margin: 20px 0 0 0;
}

.Tec{

      padding-top: 100px;
      

}

.price, .price2, .price3, .price4{
    width: 100%;
     
}

.front, .front2, .front3, .front4{
    width: 100%;
}



  
}

</style>