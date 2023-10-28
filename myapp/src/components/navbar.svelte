<script>
  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
   import "../app.css";
</script>


<Navbar  class="navbar">
  <NavBrand href="/">

    <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white devStr">&lt/Dev&gtstar </span>
  </NavBrand>
  <NavHamburger  />
  <NavUl >
    <NavLi class="navList" href="/">Home</NavLi>
    <NavLi class="navList" href="/about">About</NavLi>
    <NavLi class="navList" href="/about">About</NavLi>
    <NavLi class="navList" href="/docs/components/navbar">Roadmap</NavLi>
    <NavLi class="navList" href="/"> <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g id="evaGithubFill0"><g id="evaGithubFill1"><g id="evaGithubFill2"><g id="evaGithubFill3"><g id="evaGithubFill4"><g id="evaGithubFill5"><path id="evaGithubFill6" fill="currentColor" d="M12 1A10.89 10.89 0 0 0 1 11.77A10.79 10.79 0 0 0 8.52 22c.55.1.75-.23.75-.52v-1.83c-3.06.65-3.71-1.44-3.71-1.44a2.86 2.86 0 0 0-1.22-1.58c-1-.66.08-.65.08-.65a2.31 2.31 0 0 1 1.68 1.11a2.37 2.37 0 0 0 3.2.89a2.33 2.33 0 0 1 .7-1.44c-2.44-.27-5-1.19-5-5.32a4.15 4.15 0 0 1 1.11-2.91a3.78 3.78 0 0 1 .11-2.84s.93-.29 3 1.1a10.68 10.68 0 0 1 5.5 0c2.1-1.39 3-1.1 3-1.1a3.78 3.78 0 0 1 .11 2.84A4.15 4.15 0 0 1 19 11.2c0 4.14-2.58 5.05-5 5.32a2.5 2.5 0 0 1 .75 2v2.95c0 .35.2.63.75.52A10.8 10.8 0 0 0 23 11.77A10.89 10.89 0 0 0 12 1"/></g></g></g></g></g></g></svg></NavLi>

    <NavLi><svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path fill="white" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 6V3M8.929 8.929L6.808 6.808M6 16H3m13 13v-3m9.192-.808l-2.121-2.12M29 16h-3M8.929 23.071l-2.121 2.121M25.192 6.808l-2.12 2.121M22 16a6 6 0 1 1-12 0a6 6 0 0 1 12 0Z"/></svg></NavLi>
  </NavUl>
</Navbar>