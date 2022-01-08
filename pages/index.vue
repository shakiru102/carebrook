<template>
    <div>
      <v-app-bar dark color="#040427">
        <v-toolbar-title>Carebrook</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn text tag="a" class="nav_link hidden-sm-and-down " >Home</v-btn>
        <v-btn text tag="a" class="nav_link hidden-sm-and-down " >About</v-btn>
        <v-btn text tag="a" class="nav_link hidden-sm-and-down " >Products</v-btn>
        <v-btn text tag="a" class="nav_link hidden-sm-and-down " >Careers</v-btn>
        <v-btn text tag="a" class="nav_link hidden-sm-and-down " >Contact</v-btn>
        <v-app-bar-nav-icon dark class="hidden-md-and-up"></v-app-bar-nav-icon>
      </v-app-bar>
        <div class="section_one">
           <v-container class="py-16 px-10" >
              <v-layout row wrap>
                <v-flex xs12 sm6>
                  <div class=" text-h5 text-md-h4 mt-16">Healthcare in Africa Needs to be Rewired.</div>
                </v-flex>
                <v-flex xs12>
                  <div class="image mt-10">
                    <div class="text-h6 text-md-h4">Over 34,000 are recorded every year in Africa resulting from medical errors.</div>
                    <div class="text">Majority of these are due to lack of access to patient data and medical history.</div>
                </div>
                </v-flex>
              </v-layout>
           </v-container>
        </div>
        <div class="section_two">
          <v-container class="py-16 px-10">
            <v-layout row wrap>
              <v-flex xs12>
                <div class="padding_content ">
                  <div class=" text-h6 text-md-h4 font-weight-semibold text-center mt-16 ">Our Phones gotten smarter why not our healthcare?</div>
                  <div class="text mt-5 mb-10 text-center">Patients, medical staff, and hospitals are breaking down because of the inefficiences in our healthcare system. At carebrook, we know there is a better way.</div>
                </div>
              </v-flex>
              <v-flex xs12 sm4>
                <div class="header_title font-weight-bold mb-2 ">Easy Access</div>
                <div class=" mb-2 text pr-3">We are building a solution that improves how medical personnel access and manage patient data amd coordinate care.</div>
              </v-flex>
              <v-flex xs12 sm4>
                <div class="header_title font-weight-bold mb-2 ">Secure Exchange</div>
                <div class=" mb-2 text pr-3">When patients transfer from one hospital to another, doctors should still be able to access their previous medical data.</div>
              </v-flex>
              <v-flex xs12 sm4>
                <div class="header_title font-weight-bold mb-2 ">Better Outcomes</div>
                <div class=" mb-2 text pr-3">Our artificial intelligent platform analyzes patient data and help doctors make informed decisions and improve care</div>
              </v-flex>
              <v-flex xs12>
                <div class="text_container">
                  <div class="text-center mb-8 ">WHY YOU SHOULD USE CAREBROOK</div>
                  <div class="text-center text-sm-h6">We arm healthcare providers Africa and other emerging markets with the right tools for efficient healthcare delivery.</div>
                </div>
              </v-flex>
            </v-layout>
          </v-container>
        </div>
        <div class="section_three">
          <v-container >
            <v-layout row wrap>
              <v-flex xs12>
                <div class="text-sm-h3 text-center px-16">It is time for healthcare in Africa to enter the dataverse.</div>
              </v-flex>
              <v-flex xs12 sm6  class="pt-16 px-10">
                <div class="font-weight-bold">For Hospitals</div>
                <div class="text">Through our Electronic Healthcare Information Exchange platform, medical professionals can easily access and manage patient data and securely exchange health information. </div>
              </v-flex>
              <v-flex xs12 sm6 class="pt-16 px-10" ><v-img height="150px" contain :src="require('@/assets/undraw_medical_care_movn 1.svg')" ></v-img></v-flex>
              <v-flex xs12 sm6 class="pt-16 px-10" ><v-img height="150px" contain :src="require('@/assets/undraw_injured_9757 1.svg')" ></v-img></v-flex>
              <v-flex xs12 sm6 class="pt-16 px-10" >
                <div class="font-weight-bold">For Patients</div>
                <div class="text">Through our mobile platform, patients can communicate remotely with qualified doctors, share health information, pay for healthcare services and crowdfund for medical care. </div>
              </v-flex>
              <v-flex xs12 sm6 class="pt-16 px-10" >
                <div class="font-weight-bold">For Partners</div>
                <div class="text">Healthcare research institutions can use streamlined and accurate healthcare data for analysis and research, further improving healthcare delivery in Africa and in other developing countries. </div>
              </v-flex>
              <v-flex xs12 sm6 class="pt-16 px-10" ><v-img height="150px" contain :src="require('@/assets/undraw_medical_research_qg4d 1.svg')" ></v-img></v-flex>
                <v-flex xs12>
                <div class="text_container2">
                  <div class="text-center mb-8 ">WHY YOU SHOULD USE CAREBROOK</div>
                  <div class="text-center text-sm-h6">We arm healthcare providers Africa and other emerging markets with the right tools for efficient healthcare delivery.</div>
                </div>
              </v-flex>
            </v-layout>
          </v-container>
        </div>
        <div class="section_four">
          <v-container class="px-2">
             <v-layout row wrap>
               <v-flex xs12 sm6>
                  <div class=" text-h5 px-5 text-sm-h4">Talk to us</div>
                  <div class="text px-6 mb-2">We help healthcare providers scale to meet the challenges of healthcare with increased access, quality and efficiency.</div>
               </v-flex>
               <v-flex xs12 sm6>
                 <v-container class="pb-10" >
                   <v-layout row wrap >
                     <v-flex xs12 sm6 class=" px-1 ">
                       <v-text-field
                       placeholder="First Name"
                       solo
                       flat
                       background-color="white"
                     ></v-text-field>
                     </v-flex>
                      <v-flex xs12 sm6 class=" px-1 ">
                       <v-text-field
                       placeholder="Last Name"
                       solo
                       flat
                       background-color="white"
                     ></v-text-field>
                     </v-flex>
                      <v-flex xs12  class=" px-1 ">
                       <v-text-field
                       placeholder="Email Address"
                       solo
                       flat
                       background-color="white"
                     ></v-text-field>
                     </v-flex>
                      <v-flex xs12 sm8 class=" px-1 ">
                       <v-text-field
                       placeholder="Company/Orgainsation"
                       solo
                       flat
                       background-color="white"
                     ></v-text-field>
                     </v-flex>
                      <v-flex xs12 sm4 class=" px-1 ">
                       <v-text-field
                       placeholder="Zip/Code"
                       solo
                       flat
                       background-color="white"
                     ></v-text-field>
                     </v-flex>
                     <v-flex xs12>
                       <v-textarea flat no-resize solo placeholder="Message"></v-textarea>
                     </v-flex>
                     <v-flex xs6 class=" px-1 ">
                       <div class="text">Subscribe to our Newsletter</div>
                     </v-flex>
                     <v-flex xs6  class=" px-1 text-right">
                        <v-btn large color="#040427" dark>Send Now</v-btn>
                     </v-flex>
                   </v-layout>
                 </v-container>
               </v-flex>
             </v-layout>
          </v-container>
        </div>
        <v-footer height="200px" dark color="#040427">
           <v-container>
              <v-layout row wrap>
                <v-flex xs6>
                  <div class="title">Carebrook</div>
                </v-flex>
                <v-flex xs6>
                  <div class="caption text-right">copyright 2021</div>
                </v-flex>
              </v-layout>
           </v-container>
        </v-footer>
    </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style scoped>
 .section_one{
   height: 100vh;
 }
 .image{
   height: 500px;
   width: 80%;
   position: relative;
   background: url('../assets/Rectangle 116.png');
   display: flex;
   flex-direction:  column;
   justify-content: flex-end;
   padding: 0px 20px 30px 50px;
   color: white;
   margin: 0 auto;
 }
 .section_two{
   background: #c0f0ff;
   min-height: 100vh;
   display: flex;
   align-items: center;

 }
 .padding_content{
   padding: 0px 10em 0px 10em;
 }
 .text_container{
   min-height: 150px;
   width: 80%;
   background: #040427;
   color: white;
   position: relative;
   top: 8em;
   padding: 5px 5px 5px 10px;
   margin: 0 auto;
   display: flex;
   flex-direction: column;
   justify-content: center;
   border-radius: 5px;
 }
 .section_three{
   min-height: 100vh;
   padding-top: 8em;
 }
 .section_four{
   background: #c0f0ff;
   min-height: 100vh;
   padding-top: 8em;

 }
 .text_container2{
   min-height: 150px;
   width: 80%;
   background: #040427;
   color: white;
   position: relative;
   top: 5em;
   padding: 5px 5px 5px 10px;
   margin: 0 auto;
   display: flex;
   flex-direction: column;
   justify-content: center;
   border-radius: 5px;
 }
 @media screen and (max-width: 800px) {
 .image{
   height: 300px;
 }
   
 }

 @media screen and (max-width: 600px) {
 
   .padding_content{
   padding: 0px 1em 0px 1em;
 }
 }
</style>