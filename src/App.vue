<template>
<div id="app">
<div class="navbar fixed-top flex-row">
<div class="logo">  منصة الشروق الفضائية</div>


<ul class="desktop">
<router-link tag="li" to="/" exact> <a>الرئيسية</a> </router-link> 
<router-link tag="li" to="/programing" > <a>البرامج</a> </router-link>
<router-link tag="li" to="/Sport" > <a>رياضة</a> </router-link> 
<router-link tag="li" to="/TitleNews"> <a>عنواين الاخبار</a> </router-link> 
<router-link tag="li" to="/SharePage"> <a> الاشتراك في المنصة</a> </router-link>
<router-link tag="li" to="/ContactUs"> <a>تواصل معنا</a> </router-link>

</ul>            


<div class="Social">

      <span><div class="Facebook"> <a href="https://www.facebook.com/search/top?q=al%20jazeera%20channel%20-%20%D9%82%D9%86%D8%A7%D8%A9%20%D8%A7%D9%84%D8%AC%D8%B2%D9%8A%D8%B1%D8%A9"><i class="fab fa-facebook-f"></i></a> </div></span>
     <span><div class="Twitter"> <a href="https://twitter.com/ajarabic?lang=en"><i class="fab fa-twitter"></i></a> </div></span>
     <span><div class="Whatsapp"> <a href=""><i class="fab fa-whatsapp"></i></a> </div> </span>
     <span><div class="instgram"> <a href="https://www.instagram.com/aljazeera/"><i class="fab fa-instagram"></i></a> </div></span>
     <span><div class="google"> <a href="https://www.aljazeera.net"><i class="far fa-envelope"></i></a> </div></span>
        
</div>



<button class="navbar-toggler " type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <i class="fas fa-bars"></i>
</button>


<div class="collapse navbar-collapse" id="navbarSupportedContent">

<ul class="mobile">
<router-link tag="li" to="/" exact> <a>الرئيسية</a> </router-link> 
<router-link tag="li" to="/programing" > <a>البرامج</a> </router-link>
<router-link tag="li" to="/Sport" > <a>رياضة</a> </router-link> 
<router-link tag="li" to="/TitleNews"> <a>عنواين الاخبار</a> </router-link> 
<router-link tag="li" to="/SharePage"> <a> الاشتراك في المنصة</a> </router-link>
<router-link tag="li" to="/ContactUs"> <a>تواصل معنا</a> </router-link>
</ul> 

</div>

</div>



<router-view />
</div>
</template>







<style lang="scss">

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
    font-family: 'Heebo', sans-serif;
    font-family: 'Tajawal', sans-serif;
  
}

.navbar{
  background-color: white;
  box-shadow: 0 5px 5px 0 rgba(0, 0, 0, .7);
  color: black;
  overflow: hidden;
  direction: rtl;
  font-family: 'Heebo', sans-serif;
  font-family: 'Tajawal', sans-serif;
  font-weight: bold; 
}



.flex-row{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;

}

.logo{
    color: white;
    font-size: 20px;
    color:black;
    font-weight: bold;
  

}





li{

  display: inline-block;
  list-style: none;
  color: white;
  cursor: pointer;
  font-size: 20px;
  margin: 0 2rem ;
  position:relative;
  top:8px;



}

.mobile li{
  display: none;
}

 li a{
    color: black;
    
    &.router-link-exact-active {
      color: gold;
     
    }
  }

li a:hover{
  color: gold;
  transition: .5s all ease;
  text-decoration: none;
}


.Social span{
  display: inline-block;
  color: white;
  position: relative;
   margin:10px 5px 0 0

}

.Social span div{
  width: 40px;
  height: 40px;
  border-radius: 50%;
  cursor: pointer;
}

.Social span div:hover{
  background-color: gold;
  transition: .5s all ease;

}

.Social a {
  position: absolute;
  top: 50%;
  left: 50%;
  transform:translate(-50%, -50%);
  font-weight: 900;
  color: white;
  font-size: 23px;
  text-decoration: none;

 
}

.Facebook{
  background-color: rgb(55, 88, 143);
}

.Twitter{
  background-color: rgb(93, 154, 255);
}

.instgram{
  background-image: linear-gradient(-20deg, #fc6076 0%, #ff9a44 100%);
}

.google{
 background-color: #ff0844
}

.Whatsapp{
  background-image: linear-gradient(to top, #0ba360 0%, #3cba92 100%);
  
}


.navbar > button{
  height: 40px;
  width: 40px;
  border: 2px solid black;
  position: relative;
  display: none;

}

.fa-bars{
  color: black;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}



@media (max-width:1450px){

  .Social span{
    display: none;
  }

   .navbar .desktop li{
    display: none; 
  }


   .navbar .mobile li{
    display: block; 
    text-align: right;
    position: relative;
    right: -35px;
    margin: 10px 0 0 0;
  }

 .navbar > button{
  display: block;

 }
}




</style>
