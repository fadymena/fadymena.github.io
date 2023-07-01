<script>
  import image from "../assets/bomb.png";
</script>

<nav class="navbar">
  <!-- LOGO -->
  <div class="logo appbar">MUO</div>
  <!-- NAVIGATION MENU -->
  <ul class="nav-links">
    <!-- NAVIGATION MENUS -->
    <div class="menu">
      <li><a href="/">Home</a></li>
      <li><a href="/">Menu</a></li>
      <li><a href="/">Contact</a></li>
    </div>
  </ul>
</nav>
<nav>
  <div>
    <img src={image} class="logo bomb" alt="bomb" />
  </div>
</nav>

<style>
  .logo.bomb {
    height: 6em;
  }
  .logo.bomb:hover {
    filter: drop-shadow(0 0 2em rgba(255, 255, 255, 0.708));
  }
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    padding: 20px;
    width: 100%;
    height: 7dvb;
    position: relative;
    /* background-color: #242424; */
    background-color: teal;
    background-image: url("../assets/svelte.svg");
    background-size: cover;
    color: #fff;
    object-fit: fill;
  }

  .nav-links a {
    color: #fff;
    font-size: x-large;
  }
  /* LOGO */
  .logo.appbar {
    font-size: xx-large;
    height: max-content;
  }

  /* NAVBAR MENU */
  .menu {
    display: inline-flex;
    gap: 1em;
    font-size: 18px;
    height: min-content;
  }

  .menu li:hover {
    background-color: #4c9e9e;
    border-radius: 5px;
    transition: 0.3s ease;
  }

  .menu li {
    padding: 5px 14px;
  }
</style>
