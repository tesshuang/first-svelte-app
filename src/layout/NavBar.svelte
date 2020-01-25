<script>
  import { Link } from "svelte-routing";
</script>

<nav>
  <div class="nav-wrapper">
    <Link to="/" class="brand-logo">Logo</Link>
    <ul id="nav-mobile" class="right">
      <li><Link to="about">About</Link></li>
      <li><Link to="contact">Contact</Link></li>
    </ul>
  </div>
</nav>