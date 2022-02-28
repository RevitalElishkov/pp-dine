<template>
<section class="experience ">
  <div class="grey-right"></div>
  <div class="main-layout flex column space-between">
  <div class="exp-container flex space-between align-center">
       <img class="img-left-exp" src="@/assets/img/enjoyable.jpg" alt="enjoyable">
       <div>
       <div class="browm-element flex space-between align-center">
                <div class="circle"></div>
                <div class="line"></div>
        </div>
        <div class="card">
            <h2>The most locally sourced food</h2>
            <p>All our ingredients come directly from our farm or local fishery. 
                So you can be sure that you’re eating the freshest, most sustainable food.
            </p>
        </div>
        </div>
  </div>
  <div class="exp-container flex space-between align-center">
      <div>
       <div class="browm-element flex space-between align-center">
                <div class="circle"></div>
                <div class="line"></div>
        </div>
        <div class="card">
            <h2>Enjoyable place for all the family</h2>
            <p>Our relaxed surroundings make dining with us a great experience for everyone. 
                We can even arrange a tour of the farm before your meal.
            </p>
        </div>
        </div>
        <img class="img-right-exp" src="@/assets/img/locally.png" alt="locally">
     </div>
 </div>
    <div class="brown-lines"> 
      <div v-for="n in 6" :key="n"></div>
   </div>
  <div class="grey-left"></div>
</section>
</template>

<script>
export default {

}
</script>

<style>

</style>