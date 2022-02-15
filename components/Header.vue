<template>
  <header class="relative">
    <section class="mx-4 flex h-20 items-center justify-between sm:hidden">
      <h1 class="logo">
        <a href="index.html" class="text-4xl">WFH Store</a>
      </h1>
      <i class="fa-solid fa-bars text-3xl"></i>
    </section>
    <section
      class="absolute inset-0 flex min-h-screen w-screen flex-col items-end justify-between bg-[#1687A7]/80 p-5 text-[#D3E0EA] md:relative md:min-h-fit md:flex-row md:bg-transparent md:text-black"
    >
      <h1 class="logo w-full justify-self-start text-4xl md:w-fit">
        WFH Store
      </h1>
      <nav>
        <ul
          class="flex flex-col gap-14 text-right text-2xl md:flex-row md:text-xl"
        >
          <li>Home</li>
          <li>Categories</li>
          <li>About us</li>
          <li>My Account</li>
        </ul>
      </nav>
      <article class="">
        <span class="border-b-2 border-b-[#1687A7]">$239.00</span>
        <i
          class="fa-solid fa-bag-shopping inline-grid h-14 w-14 place-items-center rounded-full bg-[#1687A7]/80 text-3xl shadow-lg md:bg-[#1687A7] md:text-[#D3E0EA]"
        ></i>
      </article>
    </section>
  </header>
</template>

<script>
export default {}
</script>
