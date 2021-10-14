<template>
  <div class="home">
    <div class="slid">
    <HomePage 

    v-for="post in posts" 
    :key="post.id" 

    :view="post.view" 
    :title="post.title" 
    
    :prgraph="post.prgraph" 
    :prgraph2="post.prgraph2"
    :prgraph3="post.prgraph3"
    :prgraph4="post.prgraph4"
    :prgraph5="post.prgraph5"
    :prgraph6="post.prgraph6"
    :prgraph8="post.prgraph8"
    :prgraph9="post.prgraph9"
    :prgraph10="post.prgraph10"
    :prgraph11="post.prgraph11"

    :walltitle="post.walltitle"
    :wallprgraph="post.wallprgraph"

    :Video="post.Video"

    :coments1="post.coments1"
    :coments2="post.coments2"
    :coments3="post.coments3"
    :coments4="post.coments4"
    :coments5="post.coments5"
    :coments6="post.coments6"
    :Add="post.Add"

    :who="post.who" 
    :who1="post.who1"
    :who2="post.who2"
    :who3="post.who3"
    :who4="post.who4"

    :contact="post.contact" 
    :contact1="post.contact1"
    :contact2="post.contact2"
    :contact3="post.contact3"
    :contact4="post.contact4"

    :network="post.network" 
    :network1="post.network1" 
    :network2="post.network2" 
    :network3="post.network3" 
    :network4="post.network4" 
    
    :channel="post.channel"
    :channel1="post.channel1"
    :channel2="post.channel2"
    :channel3="post.channel3"
    :channel4="post.channel4"

    :more="post.more"
    />

    <FooterPage 

    v-for="post in posts" 
    :key="post.id" 

    :who="post.who" 
    :who1="post.who1"
    :who2="post.who2"
    :who3="post.who3"
    :who4="post.who4"

    :contact="post.contact" 
    :contact1="post.contact1"
    :contact2="post.contact2"
    :contact3="post.contact3"
    :contact4="post.contact4"

    :network="post.network" 
    :network1="post.network1" 
    :network2="post.network2" 
    :network3="post.network3" 
    :network4="post.network4" 
    
    :channel="post.channel"
    :channel1="post.channel1"
    :channel2="post.channel2"
    :channel3="post.channel3"
    :channel4="post.channel4"
    
    />

 
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HomePage from "@/components/HomePage.vue";
import FooterPage from "@/components/FooterPage.vue";
import JsonPost from "../json/blog-post.json";


export default {
  data: function(){
    return{
      posts: JsonPost

    };
  },
  name: "Home",
  components: {
    HomePage,
    FooterPage

  
  },
};
</script>

<style lang="scss" scoped>

</style>





