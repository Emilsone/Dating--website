<template>
  <section>
    <footer class="text-white bg-black body-font">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-wrap md:text-left text-center order-first">
          <div class="lg:w-1/4 md:w-1/2 w-full px-4">
            <h2 class="title-font font-medium text-lg text-white   mb-3">
              CATEGORIES
            </h2>
            <nav class="list-none mb-10 pr-6">
              <span
                ><i class="fa fa-facebook  px-4 text-xl" aria-hidden="true"></i
              ></span>
              <span
                ><i class="fa fa-instagram  px-4 text-xl" aria-hidden="true"></i
              ></span>
              <span
                ><i class="fa fa-twitter  px-4 text-xl" aria-hidden="true"></i
              ></span>
            </nav>
          </div>
          <div class="lg:w-1/4 md:w-1/2 w-full px-4">
            <h2
              class="title-font font-medium text-lg text-white tracking-widest text-sm mb-3"
            >
              CATEGORIES
            </h2>
            <!-- <nav class="list-none mb-10">
                <li>
                  <a class="text-gray-600 hover:text-gray-800">First Link</a>
                </li>
                <li>
                  <a class="text-gray-600 hover:text-gray-800">Second Link</a>
                </li>
                <li>
                  <a class="text-gray-600 hover:text-gray-800">Third Link</a>
                </li>
                <li>
                  <a class="text-gray-600 hover:text-gray-800">Fourth Link</a>
                </li>
              </nav> -->
          </div>
          <div class="lg:w-1/4 md:w-1/2 w-full px-4">
            <h2
              class="title-font font-medium text-lg tracking-widest text-sm mb-3"
            >
              CATEGORIES
            </h2>
          </div>
          <div class="lg:w-1/4 md:w-1/2 w-full px-4">
            <h2
              class="title-font font-medium text-lg tracking-widest text-sm mb-3"
            >
              SUBSCRIBE
            </h2>
            <div
              class="flex xl:flex-no-wrap md:flex-no-wrap lg:flex-wrap flex-wrap justify-center md:justify-start"
            >
              <input
                class="w-40 sm:w-auto bg-gray-100  xl:mr-4 lg:mr-0 sm:mr-4 mr-2 border border-gray-400 focus:outline-none focus:border-indigo-500 text-base py-2 px-4"
                placeholder="Placeholder"
                type="text"
              />
              <!-- <button
                  class="lg:mt-2 xl:mt-0 flex-shrink-0 inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded"
                >
                  Button
                </button> -->
            </div>
          </div>
        </div>
        <div
          class="container  px-5 py-6 mx-auto flex items-center sm:flex-row flex-col"
        >
          <a
            class="flex title-font font-medium items-center md:justify-start justify-center "
          >
            
            <span class="ml-3 text-xl">Emilson</span>
          </a>
          <p class="text-sm text-gray-500 sm:ml-6 sm:mt-0 mt-4">
            © 2020 Emilson —
          </p>
        </div>
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
  .fa-facebook,
  .fa-twitter,
  .fa-instagram {
    font-size: 13px;
  }
}
</style>
