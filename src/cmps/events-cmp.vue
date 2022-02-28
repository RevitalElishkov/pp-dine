<template>
  <section class="events">
    <div class="grey-decor"></div>
    <div class="brown-lines"> 
      <div v-for="n in 6" :key="n"></div>
   </div>
      <div class="event-container main-layout">
        <img src="@/assets/img/gathering.png" alt="gathering">
        <div class="brown-event-line"></div>
        <div class="flex column">
          <div class="card">
            <h2>Family Gathering</h2>
            <p>We love catering for entire families. So please bring everyone along for a special meal with your loved ones. 
              We’ll provide a memorable experience for all.
            </p>
          </div>
            <button class="book-btn">book a table</button>
          <div class="event-list">
            <p> <span> family gathering </span> </p> 
            <p> special events </p>
            <p> social events </p>
          </div>
        </div>
      </div>

  </section>
</template>

<script>
export default {

}
</script>

<style>

</style>