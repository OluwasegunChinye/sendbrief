<template>
  <v-container class="mt-10" >
    <v-row wrap class="">
      <v-col cols="12" md="6" >
        <v-card elevation="0">
          <v-card-text>
            <p class=" font-weight-bold" style="color:#362d62; font-size:48px; line-height:60px;" >Sharing and Managing your <strong style="color:#db2763"> Briefs </strong> just got alot easier</p>
            <p  class="justify mt-10" style="color: #362d62"><strong style="color:#db2763">Sendbrief </strong>allows you send or share customer-tailored briefs that contain <strong style="color:#2ec6a8"> Videos</strong>, <strong style="color:#2ec6a8"> Pictures</strong>, <strong style="color:#2ec6a8">Documents</strong> and <strong style="color:#2ec6a8">Voice notes </strong>all in one link and click.</p>
          </v-card-text>

          <v-card-actions class="mt-15">
           <a href="" target="_blank" rel="noopener noreferrer"><v-img alt="" class="mr-4 ml-2" contain src="../assets/apple_btn03.svg" transition="scale-transition" width="160"></v-img></a>

           <a href="" target="_blank" rel="noopener noreferrer"><v-img alt="" contain src="../assets/playstore_btn01.svg" transition="scale-transition" width="160"></v-img></a>
          </v-card-actions> 
        </v-card>
      </v-col>
      
      <v-col cols="12" md="6">
        <!-- <v-card elevation="1" class="" > -->
          <img src="../assets/mock01.svg" alt="" srcset="" height="500" style="display: block; margin: 0 auto;">
        <!-- </v-card> -->
      </v-col>
    </v-row>

    <Section1/>
  </v-container>

  
</template>



<script>
import Section1 from "@/components/Section1.vue"

export default {
    components:{
        Section1,
    }
}
</script>

<style>

</style>