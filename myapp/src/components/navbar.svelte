<script>
  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
   import "../app.css";
</script>


<Navbar  class="navbar">
  <NavBrand href="/">

    <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white devStr">&lt/Devstar&gtstar </span>
  </NavBrand>
  <NavHamburger  />
  <NavUl >
    <NavLi class="navList" href="/">Home</NavLi>
    <NavLi class="navList" href="/about">About</NavLi>
    <NavLi class="navList" href="/about">About</NavLi>
    <NavLi class="navList" href="/docs/components/navbar">Roadmap</NavLi>
  </NavUl>
</Navbar>