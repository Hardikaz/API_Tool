<script>
  import Navbar from "./components/navbar.svelte";
  import Upper from "./components/upcontent.svelte";
  import ApiBox from "./components/apiContainer.svelte";
  import Footer from "./components/footer.svelte";
  import "./app.css";
  import('tailwindcss').Config;
</script>

<body class="app">
<Navbar />
<Upper />
<ApiBox />
<Footer />
</body>

 