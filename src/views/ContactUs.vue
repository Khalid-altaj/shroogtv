<template>
    <div class="culture">

    <ContactUs v-for="post in posts" 
    :key="post.id" 
    :book1="post.book1" 
    :bo="post.bo" 
    :book2="post.book2" 
    :bo2="post.bo2" 
    :book3="post.book3" 
    :bo3="post.bo3" 
    :book4="post.book4" 
    :bo4="post.bo4" 
    :book5="post.book5" 
    :bo5="post.bo5" 
    :book6="post.book6" 
    :bo6="post.bo6" />



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

import ContactUs from "@/components/ContactUs.vue";
import FooterPage from "@/components/FooterPage.vue";
import JsonPost from "../json/blog-post.json";


export default {

    data: function(){
    return{
      posts: JsonPost

    };
  },
  
    name: "culture",

    components: {
    ContactUs,
    FooterPage
  },
    
}
</script>

