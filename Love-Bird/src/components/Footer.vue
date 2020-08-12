<template>
  <section>
    <footer class="bg-black h-full text-white p-8">
      <div class="container flex flex-wrap justify-around">
        <div class="icons">
          <h1 class="text-2xl py-12">FOLLOW US</h1>
          <span
            ><i class="fa fa-facebook  px-4 text-xl" aria-hidden="true"></i
          ></span>
          <span
            ><i class="fa fa-instagram  px-4 text-xl" aria-hidden="true"></i
          ></span>
          <span
            ><i class="fa fa-twitter  px-4 text-xl" aria-hidden="true"></i
          ></span>
          <!-- <span><i class="fa fa-sna  px-6 text-4xl" aria-hidden="true"></i></span> -->
        </div>
        <div><h1 class="text-2xl py-12">CONTACT US</h1></div>
        <div>
          <h1 class="text-2xl py-12">SUSCRIBE</h1>

          <input
            class="bg-gray-200 appearance-none my-4 border-gray-200  w-42 py-4 px-12 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500"
            id="inline-username"
            type="email"
            placeholder="Enter your email"
          />
        </div>
      </div>
    </footer>
    <footer>
      <div class="container">
        <h1 class="text-center"></h1>
      </div>
    </footer>
  </section>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style scoped>
.container {
  background-color: black;
  color: white;
}

.fa-facebook:hover {
  color: #e04652;
}
.fa-instagram:hover {
  color: #e04652;
}
.fa-twitter:hover {
  color: #e04652;
}
@media (max-width: 755px) {
  .container {
    flex-direction: column;
    text-align: center;
  }
  .icons {
    text-align: center;
  }
  .fa-facebook,.fa-twitter,.fa-instagram{
  font-size: 19px;
}
}
</style>
