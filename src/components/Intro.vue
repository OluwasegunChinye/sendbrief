<template>
  <v-container fluid class="mt-10" >
    <v-row wrap class="">
      <v-col cols="12" md="5">
        <v-card elevation="0">
          <v-card-text>
            <p class="display-2 font-weight-bold" style="color:#362d62; line-height:" >Managing your <strong style="color:#db2763"> Briefs </strong> just got alot easier</p>
            <p  class="justify mt-10" style="color: #362d62"><strong style="color:#db2763">Sendbrief </strong>allows you send or share customer-tailored briefs that contain <strong style="color:#2ec6a8"> Videos</strong>, <strong style="color:#2ec6a8"> Pictures</strong>, <strong style="color:#2ec6a8">Documents</strong> and <strong style="color:#2ec6a8">Voice notes </strong>all in one link and click.</p>
          </v-card-text>

          <v-card-actions class="mt-15 justify-start">
           <a href="" target="_blank" rel="noopener noreferrer"><v-img alt="" class="mr-4" contain src="../assets/apple_btn02.svg" transition="scale-transition" width="120"></v-img></a>

           <a href="" target="_blank" rel="noopener noreferrer"><v-img alt="" contain src="../assets/playstore_btn02.svg" transition="scale-transition" width="120"></v-img></a>
          </v-card-actions> 
        </v-card>
      </v-col>
      
      <v-col cols="12" md="7">
        <v-card elevation="0" class="d-flex justify-center " >
          <img src="../assets/mock001.svg"  contain height="500px" alt="" srcset="">
        </v-card>
      </v-col> 
    </v-row>
    <section1/>
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