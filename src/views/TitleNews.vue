<template>
    <div class="Price">

  <TitleNews v-for="post in posts" 
  :key="post.id" 
  :jaina="post.jaina" 
  :sub="post.sub" 
  :sudan="post.sudan" 
  :sub2="post.sub2" 
  :obc="post.obc" 
  :sub3="post.sub3" 
  :home="post.home" 
  :sub4="post.sub4"
  :btc="post.btc"
  :sub5="post.sub5"
  :usa="post.usa"
  :sub6="post.sub6"/>


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
</template>


<script>

import TitleNews from "@/components/TitleNews.vue";
import FooterPage from "@/components/FooterPage.vue";
import JsonPost from "../json/blog-post.json";


export default {

    data: function(){
    return{
      posts: JsonPost

    };
  },
  
    name: "Price",

    components: {
    TitleNews,
    FooterPage
  },
    
}
</script>

