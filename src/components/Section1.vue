<template>
   <v-row wrap >
      <v-col cols="12" class="pa-2 my-5" outlined tile>
        <!-- <v-card class="pa-2" outlined tile > -->
          <div>
            <p class="mt-15 mb-10" style="text-align: center; font-size:36px; font-weight: bold; color:#362d62">
            <strong style="font-size:40px; color:#db2763;">Agents </strong>  work smart with Sendbrief
            </p>
          </div>
        <!-- </v-card> -->
    
        <v-row wrap>
          <v-col cols="12" md="5" class="hidden-xs-only">
            <div>
              <v-img alt="sendbrief logo" class="shrink " contain src="../assets/user_img2.png" transition="scale-transition" height="500" style="display: block; margin: 0 auto;" />
            </div>
          </v-col>

          <v-col  cols="12" md="7">
            <v-row wrap d-flex >
              <v-col cols="6" md="4" class="" outlined tile v-for="(card,index) in cards" :key="index" >
                <v-card height="220" elevation="0" outlined color="" class="pa-3" style="border-radius:8px; border:1px solid #d1f4ed ">
                  <!-- <v-card-text> -->
                    <div style="color:#2ec6a8">
                      <i class=" mb-2 far fa-check-circle fa-lg"></i>
                    </div>
                    <span style="font-size:14px; font-weight:bold; color:#362d62">{{card.title}}</span>
                    <p class="mt-1" style="font-size:12px; color:#362d62; text-align:">
                     {{card.body}}
                    </p>
                  <!-- </v-card-text> -->
                </v-card>
              </v-col>
            </v-row>
          </v-col>            
        </v-row>
      </v-col>
    </v-row>
</template>

<script>
export default {
  data(){
    return {
      cards: [
        {title:"Matching", body:"Match clients with targeted briefs, each client getting specific briefs"},
        {title:"Four in One", body:"Share briefs that contain Videos, Pictures, Documents and Voice-notes with your clients, all in one link post"},
        {title:"Direct Contact", body:"Interested Clients can contact you directly from any location after viewing your brief. Yes, your brief carries your contact profile"},
        {title:"Referral Marketing Tool", body:"Briefs can be shared multiple times over, meaning, your clients can share same brief with their own contacts and likewise. Every person that views your brief can contact you directly. "},
        {title:"Get Organized", body:"Thats right, you can carefully organise all briefs into the App. Decluster your phone and stop wasting time searching through your phone"},
        {title:"Cloud Storage", body:" If anything happens to your device be rest assured, All briefs are safe in the cloud"},
      ]
    }
  }
}
</script>

<style>

</style>