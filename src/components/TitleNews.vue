<template>

<div class="PricePage">
    <div class="container">
<div class="row">  

<div class="col-lg-9 col-md-12 col-sm-12 col-xs-12">
             
<div class="middle33"> 
<div class="container">
<div class="mov">
    
<h4> {{jaina}} </h4>  <p> {{sub}} </p>
        </div>
    </div>

</div>

</div> 


<div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">
            
<div class="left33"> <img src="../assets/world.jpg" > </div>

</div>




 <div class="col-lg-9 col-md-12 col-sm-12 col-xs-12">
             
<div class="middle33">
    <div class="container">
        <div class="mov">

    <h4> {{sudan}} </h4>  <p> {{sub2}} </p>
        </div>
    </div>
            
</div></div>


<div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">
            
<div class="left33"> <img src="../assets/sudan.jpg" > </div>

</div>



<div class="col-lg-9 col-md-12 col-sm-12 col-xs-12">
             
<div class="middle33">
    <div class="container">
        <div class="mov">

    <h4> {{obc}} </h4>  <p> {{sub3}} </p>
        </div>
    </div>
            
</div></div>


<div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">
            
<div class="left33"> <img src="../assets/obc.jpg" > </div>

</div>



<div class="col-lg-9 col-md-12 col-sm-12 col-xs-12">
             
<div class="middle33">
    <div class="container">
        <div class="mov">

    <h4> {{home}} </h4>  <p> {{sub4}} </p>
        </div>
    </div>
            
</div></div>

  

<div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">

 <div class="left33"> <img src="../assets/home.jpg" > </div>

</div>




<div class="col-lg-9 col-md-12 col-sm-12 col-xs-12">
             
<div class="middle33">
    <div class="container">
        <div class="mov">

    <h4> {{btc}} </h4>  <p> {{sub5}} </p>
        </div>
    </div>
            
</div></div>


<div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">
            
<div class="left33"> <img src="../assets/btc.jpg" > </div>

</div>



<div class="col-lg-9 col-md-12 col-sm-12 col-xs-12">
             
<div class="middle33">
    <div class="container">
        <div class="mov">

    <h4> {{usa}} </h4>  <p> {{sub6}} </p>
        </div>

    </div>
            
</div></div>

  

<div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">
            
<div class="left33"> <img src="../assets/usa.jpg" ></div>

</div>

</div>

</div>
</div>

</template>


<script>
export default {
    name : "PricePage",
    props : ["jaina", "sub", "sudan", "sub2", "obc", "sub3", "home", "sub4", "btc", "sub5", "usa", "sub6"]
}
</script>

<style lang="scss" scoped>

.PricePage{
    padding-top: 100px;
}

.left33{
  
    background-color: white;
   box-shadow: 2px 5px 5px 2px rgba(0, 0, 0, .5);
    margin: 20px 0 0 0;
    height: 140px;
    position: relative;

}

@media (max-width:767px) {

    .left33{
        margin: 20px 0 20px 0;
    }
    
}


.left33 img{
    width: 95%;
    height: 90%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);

}



.middle33{
    position: relative;
    padding-top: 20px;
    padding-bottom: 20px;
    margin: auto;
    background-color: white;
    box-shadow: 2px 5px 5px 2px rgba(0, 0, 0, .5);
    margin: 20px 0 0 0;

}

.middle33 h4{
  font-family: 'Heebo', sans-serif;
  font-family: 'Tajawal', sans-serif;
  text-align: right;
    font-weight: bold;
  font-size: 20px;
}

.middle33 p{
    font-family: 'Heebo', sans-serif;
  font-family: 'Tajawal', sans-serif;
  font-size: 18px;
  color: #011f75;
  text-align: right;
}


</style>