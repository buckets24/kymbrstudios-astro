<script>

</script>

<div>
    <header class="main_nav">
    <div class="main_nav__container">
      <a
        href="/"
      >
        <img class="main_nav__logo" src="./assets/kymbrstudios.png" alt="kymbrstudios" />
      </a>
      <div class="main_nav__nav_list">
        <div class="main_nav__nav_list__item">
          <a class="main_nav__nav_item" href="#about">About</a>
        </div>
        <div class="main_nav__nav_list__item">
          <a class="main_nav__nav_item" href="#services">Services</a>
        </div>
        <div class="main_nav__nav_list__item">
          <a class="main_nav__nav_item" href="#contact">Contact</a>
        </div>
      </div>
    </div>
  </header>
</div>

<style>
.main_nav {
  background-color: rgba(0,0,0,0.8);
  position: fixed;
  z-index: 2;
  width: 100%;
}


.main_nav__container {
  padding: 20px 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.main_nav__logo {
  margin: 0;
}

.main_nav__nav_item {
  text-transform: uppercase;
  font-weight: 700;
  color: #FFFFFF;
  padding: 10px;
  display: none;
  text-decoration: none;
}

.main_nav__nav_list {
  display: flex;
  list-style-type: none;
  margin: 0;
}

.main_nav__nav_list__item {
  display: flex;
  list-style-type: none;
  margin: 0;
}

@media only screen and (min-width: 768px) {
  .main_nav__container  {
    justify-content: space-between;
  }

  .main_nav__nav_item {
    display: flex;
  }
}

@media only screen and (min-width: 1024px) {
  .main_nav__container  {
    justify-content: space-between;
  }

  .main_nav__nav_item {
    display: flex;
  }
}
</style>