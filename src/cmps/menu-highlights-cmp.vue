<template>
  <section class="menu main-layout flex column"> 
      <div class="container">
           <div class="browm-element flex space-between align-center">
                <div class="circle"></div>
                <div class="line"></div>
            </div>
        <div class="flex space-between">
        <div class="card">
            <h2>A few highlights from our menu</h2>
            <p>We cater for all dietary requirements, but here’s a glimpse at some of our diner’s favourites. 
                <br/>Our menu is revamped every season.</p>
        </div>
        <div class="meals">
            <div v-for="meal in meals" :key="meal.mealName" class="meal flex">
                <img :src="require(`@/assets/img/${meal.imgSrc}`)"  />
                <div class="brown-line"></div>
                <div class="meal-info">
                    <h3> <span> {{ meal.mealName }} </span> </h3>
                    <p> {{ meal.mealDesc }} </p>

                </div>
            </div>
        </div>
        </div>
        </div>
  </section>
</template>

<script>
export default {
data() {
    return {
        meals: [
        {
            imgSrc: 'salmon.jpg',
            mealName:'Seared Salmon Fillet',
            mealDesc: 'Our locally sourced salmon served with a refreshing buckwheat summer salad.'
        },
        {
            imgSrc: 'mignon.jpg',
            mealName: 'Rosemary Filet Mignon',
            mealDesc: 'Our locally sourced salmon served with a refreshing buckwheat summer salad.'
        },
        {
            imgSrc: 'mousse.png',
            mealName: 'Summer Fruit Chocolate Mousse',
            mealDesc: 'Our locally sourced salmon served with a refreshing buckwheat summer salad.'
        }
    ],
    }
    }
}
</script>

<style>

</style>