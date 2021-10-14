<template>
    <div class="Tec">

    <SharePage v-for="post in posts" :key="post.id" :doc="post.doc" :ddoc="post.ddoc" :whats="post.whats" :wh="post.wh" :fac="post.fac" :fsub="post.fsub" :cash="post.cash" :csub="post.csub" :man="post.man" :msub="post.msub" :car="post.car" :carsub="post.carsub"/>

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

import SharePage from "@/components/SharePage.vue";
import FooterPage from "@/components/FooterPage.vue";
import JsonPost from "../json/blog-post.json";


export default {

    data: function(){
    return{
      posts: JsonPost

    };
  },
  
    name: "Tec",

    components: {
    SharePage,
    FooterPage
  },
    
}
</script>

