<template>
  <section class="section ">
    <div class="container flex flex-wrap sm:mx-12 justify-around">
 <div class="text text-white my-48">
          <h1 class=" font-bold text-6xl" id="love">Find The Love <br>Of Your Life!!!</h1>
          <p class="lorem py-8">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea eum 
            voluptas officiis<br> ad et  illum consequatur earum, ut
             placeat <br>necessitatibus voluptatum vel tempora eius quod beatae labore.</p>

             <div class="button">
             <button
            class="bg-gray-300 w-42 h-12 hover:bg-gray-400 text-gray-800 py-2 px-6 my-6 rounded inline-flex items-center" id="button">
            Read More
          </button>

             </div>
      </div>
    <div class="w-full max-w-xs my-48 ">
      <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4 "  id="form">
        <div class="mb-4 mt-6">
          <h1 class="text-xl font-bold pb-12" >FND YOUR INSTANT DATE</h1>
          <label
            class="block text-gray-700 text-sm font-bold mb-2"
            for="username"
          >
            Username <i class="fa fa-id-card-o" aria-hidden="true"></i>
          </label>
          <input
            class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
            id="username"
            type="text"
            placeholder="Username"
          />
        </div>
        <div class="mb-6">
          <label
            class="block text-gray-700 text-sm font-bold mb-2"
            for="password"
          >
            Password
          </label>
          <input
            class="shadow appearance-none border border-red-500 rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline"
            id="password"
            type="password"
            placeholder="******************"
          />
          <p class="text-red-500 text-xs italic">Please choose a password.</p>
        </div>
        <div class="flex items-center justify-between">
          <button
            class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline mx-auto w-42"
            type="button"
          >
          Register
          </button>
          
        </div>
      </form>
    </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Banner",
};
</script>
<style>
.section {
  background-image: url("../assets/home-banner.jpg");
  background-position: center;
  background-attachment: fixed;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-blend-mode: soft-light;
  background-color: rgb(22, 20, 20);
}
@media  (max-width: 755px){
  #form{
    visibility: hidden;
  }
  #love{
    font-size: 40px;
    text-align: center;
    font-weight: 700;
  }
  .button{
    text-align: center
  }
  .lorem{
    text-align: center;
    font-size: 15px;
    padding: 10px 9px 9px 10px;
  }
  #button{
    background-color: transparent;
    border: 2px solid white;
    color: #ffffff;
  }
}
</style>
