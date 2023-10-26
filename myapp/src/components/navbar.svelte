<script>
  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>


<Navbar  >
  <NavBrand href="/">

    <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">&lt/Devstar&gtstar </span>
  </NavBrand>
  <NavHamburger  />
  <NavUl >
    <NavLi href="/">Home</NavLi>
    <NavLi href="/about">About</NavLi>
    <NavLi href="/docs/components/navbar">Roadmap</NavLi>
  </NavUl>
</Navbar>