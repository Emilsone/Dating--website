<template>
  <section>
    <footer class="bg-black h-48 text-white p-8">
      <div class="container flex flex-wrap justify-around">
        <div>
          <h1 class="text-2xl py-8">FOLLOW US</h1>
        </div>
        <div><h1 class="text-2xl py-8">CONTACT US</h1></div>
        <div>
          <h1 class="text-2xl py-8">SUSCRIBE</h1>
          <div class="md:w-2/3">
            <input
              class="bg-gray-200 appearance-none border-2 border-gray-200 rounded w-42 py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-purple-500"
              id="inline-username"
              type="email"
              placeholder="Enter your email"
            />
            <!-- <button>ABS</button> -->
          </div>
        </div>
      </div>
    </footer>
    <footer>
      <div class="container w-full">
        <h1 class="text-center">copy right reserved by mr Vue</h1>
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
</style>
