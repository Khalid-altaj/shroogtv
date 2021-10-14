<template>
    <div class="programing">

  <ProgramingPage v-for="post in posts" 
  :key="post.id" 
  :programing="post.programing" 
  :programing2="post.programing2" 
  :programing3="post.programing3" 
  :programing4="post.programing4"/>

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

import ProgramingPage from "@/components/ProgramingPage.vue";
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
    ProgramingPage,
    FooterPage

  },
    
}
</script>