<script>
  import Sidebar from './lib/sidebar.svelte';
  import Navbar from './lib/navbar.svelte';
  import About from './lib/about.svelte';
  import Resume from './lib/resume.svelte';
  import Portfolio from './lib/portfolio.svelte';
  import Blog from './lib/blog.svelte';
  import Contact from './lib/contact.svelte';
  import './script'
</script>

<main>
  <Sidebar/>
  <div class="main-content">
    <Navbar/>
    <About/>
    <Resume/>
    <Portfolio/>
    <Blog/>
    <Contact/>
  </div>
</main>