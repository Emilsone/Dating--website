<template>
  <section class="bg-gray-200">
      <div>
          <h1 class="text-4xl text-center font-bold py-8 pt-8">{{heading}}</h1>
      </div>
    <div class="container  flex flex-wrap justify-around pt-4 py-48">
      <div>
        <img src="../assets/journey-4.jpg" class="w-58"  alt="" />
        <h1 class="heading-name  pt-4">{{hena}}</h1>
        <p class=" py-2">{{age}}</p>
      </div>
      <div>
        <img src="../assets/journey-5.jpg" class="w-58" alt="" />
        <h1 class="heading-name pt-4">{{hena}}</h1>
        <p class="py-2">{{age}}</p>
      </div>
      <div>
        <img src="../assets/journey-6.jpg" class="w-58" alt="" />
        <h1 class="heading-name pt-4">{{hena}}</h1>
        <p class="py-2">{{age}}</p>
      </div>
      <div>
        <img src="../assets/journey-5.jpg" class="w-58" alt="" />
        <h1 class="heading-name pt-4">{{hena}}</h1>
        <p class="py-2">{{age}}</p>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Profile",
  data:()=>{
    return{
      heading:"Last Added Profiles",
      hena:"Hena Smith",
      age:"Age 22, UK"

    }
   
  }
};
</script>
<style scoped>
.heading-name{
color: #E04652;
}
@media  (max-width: 755px){
  /* img{
    width: 100%;
    height: 90%;
  } */
}
</style>

