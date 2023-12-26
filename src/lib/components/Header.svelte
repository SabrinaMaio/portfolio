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
    h2 {
      color: orange;
    }
  
    header {
      color: black;
  
      nav {
        ul {
          list-style: none;
          display: flex; /* Aligne les éléments horizontalement */
          padding: 0;
        }
  
        li {
          background: lightgray;
          margin-right: 10px; /* Ajoute une marge entre les éléments */
        }
  
        a {
          text-decoration: none;
          color: inherit;
        }
      }
    }
  </style>