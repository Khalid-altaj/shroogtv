<template>
<footer>
<div class="mycontainer">
<img src="../assets/الشروق.jpg">
<div class="row">
  <div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">
    <p> {{who}} <i class="fas fa-users"></i></p>


    <h5> {{ who4 }} </h5>

    <h5> {{ who1 }} </h5>

    <h5> {{ who2 }} </h5>

    <h5> {{ who3 }} </h5>



  </div>

  <div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">

    <p> {{contact}} <i class="fas fa-mobile-alt"></i> </p>

    <h5> {{ contact1 }} </h5>

    <h5> {{ contact2 }} </h5>

    <h5> {{ contact3 }} </h5>

    <h5> {{ contact4 }} </h5>


  </div>

  <div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">

    <p> {{network}} <i class="fas fa-wifi"></i> </p>

    <h5> {{ network3 }} </h5>

    <h5> {{ network1 }} </h5>

    <h5> {{ network2 }} </h5>

    <h5> {{ network4 }} </h5>

  </div>

  <div class="col-lg-3 col-md-12 col-sm-12 col-xs-12">

    <p>{{ channel }} <i class="fas fa-tv"></i> </p>

    <h5> {{ channel1 }} </h5>

    <h5> {{ channel2 }} </h5>

    <h5> {{ channel3 }} </h5>

    <h5> {{ channel4 }} </h5>

</div>
</div>
</div>
</footer>
</template>

<script>
export default {
  name: "FooterPage",
  props: [

    "who", "contact", "network", "channel",
    "who1",
    "who2",
    "who3", 
    "who4", 

    "contact1", 
    "contact2", 
    "contact3", 
    "contact4", 

    "network1", 
    "network2", 
    "network3", 
    "network4", 

    "channel1", 
    "channel2", 
    "channel3", 
    "channel4", 
      
    ]
};
</script>

<style lang="scss" scoped>
footer{
    background-color: white;
    width: 100%;
    margin: 40px 0 0 0;
  

.mycontainer{
  padding-left: 40px;
  padding-right: 40px;
}
    

    p{
        font-family: 'Heebo', sans-serif;
        font-family: 'Tajawal', sans-serif;
        font-weight: bold;
        font-size: 25px;
        color: #fec300;
        padding: 70px 0 0 0;
        
    }
     

    h5{
      font-family: 'Heebo', sans-serif;
      font-family: 'Tajawal', sans-serif;
       color: #011f75;
      font-weight: bold;
      cursor: pointer;
      margin: 30px 0;
      font-size: 18px;
    }
     h4:hover{
           color: #fec300;
         }

        
    img{
     padding:40px 0 0 0;
     width: 150px;
       }

       


}
</style>