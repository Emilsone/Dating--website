<template>
  <section>
    <div class="container flex  justify-between my-12">
      <div class="text-img">
        <img src="../assets/love-bird.jpg" class="w-3/4 h-42 mx-8" alt="" />
      </div>
      <div class="text-banner pt-4">
        <h1 class="text-6xl  font-bold py-8 pt-8 px-4">Welcome!</h1>
        <p class="text-md px-4">
          Luis is a long established dating agency (est . since <br />1996) We
          have successfully conected thousands of singles<br />
          together with our personal 'one on one' compatibility <br />system.
          Our database of single men and women is the<br />
          largest in the area, so we really do have somebody for
        </p>
        <h1 class="text-2xl  font-bold py-8 pt-8 px-4">Tired Of Being Alone We're Here To Help You</h1>
         <button
            class="bg-gray-300 w-42 h-12 hover:bg-gray-400 text-gray-800 py-2 px-6 my-6 mx-4 rounded inline-flex items-center">
            Read More
          </button>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name:"Welcome"
}
</script>
<style scoped>
@media  (max-width: 755px){
  img{
    width: auto;
    height: auto;
    margin: auto;
  }
   .container{
    flex-direction: column;
    
  }
  .text-banner{
    margin-left: 10px;
  }
  .welcome{
    text-align:center ;
  }
}
</style>

