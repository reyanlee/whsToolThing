<template>

<v-container>

       <v-layout row justify-center align-center wrap>
           <v-flex >
               <v-subheader id="language title" class="title mt-1">World Languages</v-subheader>

               <v-card class=" auto-grow grey lighten-3 mx-5 mt-3" fluid>

                   <v-card-title primary-title height="100px">
                       <h3 class="mb-0 headline">
                           Algebra 1
                       </h3>
                   </v-card-title>

                   <v-subheader class="pt-0 mt-0">
                       1 Credit - Open to Grades 9-12
                   </v-subheader>

                    <v-card-text class="grow">
                       This standard first-year course in algebra includes the real number system, first degree equations of one or two variables, polynomials, graphing, quadratic equations, exponents and radicals. Students will learn to use symbolic forms to represent, model and analyze mathematical situations. (Algebra is a prerequisite for chemistry.)
                   </v-card-text>

               </v-card>

               <v-card class="auto-grow grey lighten-3 mx-5 mt-3" fluid>

                   <v-card-title primary-title height="100px">
                       <h3 class="mb-0 pb-0 headline">
                           Modeling Our World 1
                       </h3>
                   </v-card-title>

                   <v-subheader class="pt-0 mt-0">
                       1 Credit - Open to Grade 9<br>
                   </v-subheader>

                   <v-card-text class="grow">
                       This course focuses upon the use of modeling to represent mathematical and real-world contexts. The application and creation of mathematical models engages students in learning experiences that relates classroom mathematics to everyday life and decision-making. The content of the course focuses upon specific learning expectations defined in the Common Core State Standards for high school mathematics, particularly those standards emphasizing the use of mathematical modeling with linear and exponential functions. The course is intended to be taken concurrently with Algebra I, to provide supplemental learning opportunities for students needing additional support to be successful in Algebra I. 
                   </v-card-text>

               </v-card>

           </v-flex>
       </v-layout>

   </v-container>

</template>

<script>
 export default {
   data: () => ({
       cards: []
   })
 }
</script>
