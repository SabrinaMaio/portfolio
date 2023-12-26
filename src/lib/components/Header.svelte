<script>
    import {link} from "svelte-spa-router";
</script>

<header>
    <nav>
        <ul>
            <li><a use:link href="/">Accueil</a></li>
            <li><a use:link href="/portfolio">Portfolio</a></li>
            <li><a use:link href="/contact">Contact</a></li>
        </ul>
    </nav>
</header>



<style lang="scss">
  header {
    color: black;

    nav {
      ul {
        list-style: none;
        display: flex; 
        justify-content: flex-end; 
        padding: 0;
        font-size: 1.4rem;
      }

      li {
        
        margin-left: 10px; 
      }

      a {
        text-decoration: none;
        color: inherit;
      }
    }
  }
</style>
