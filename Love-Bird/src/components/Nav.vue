<template>
  <header
    class="lg:px-16 px-6 bg-white flex flex-wrap items-center lg:py-0 py-4"
  >
    <div class="flex-1 flex justify-between items-center">
      <a href="#">
        <img src="../assets/logo.png" alt=" love logo" class="mr-8 w-32" />
        <!-- <h1 class="text-2xl">Louis Birds</h1> -->
      </a>
    </div>

    <label for="menu-toggle" class="pointer-cursor lg:hidden block"
      ><svg
        class="fill-current text-gray-900"
        xmlns="http://www.w3.org/2000/svg"
        width="20"
        height="20"
        viewBox="0 0 20 20"
      >
        <title>menu</title>
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path></svg
    ></label>
    <input class="hidden" type="checkbox" id="menu-toggle" />

    <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
      <nav>
        <ul
          class="lg:flex items-center justify-between text-base text-gray-700 pt-4 lg:pt-0"
        >
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >HOME
            </a>
          </li>
          <li>
            <a
              class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >HOW IT WORKS</a
            >
          </li>
          <li>
            <a
              class="lg:p-4 py-3 px-0 lock border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >HELP</a
            >
          </li>
          <li>
            <a
              class="lg:p-4 py-4 px-0 lock border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >Login</a
            >
          </li>
          <li>
            <a
              class="lg:p-4 py-4 px-0 lock border-b-2 border-transparent hover:border-indigo-400"
              href="#"
              >Register</a
            >
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Nav",
};
</script>
<style>
#menu-toggle:checked + #menu {
  display: block;
}
</style>
