<template>
  <div class="navbar">
  <a class="home" href="#">Home</a>
  <a href="#">Search</a>
  <a href="#">Contact</a>
  <a href="#">Login</a>
</div>
</template>

<style>
.navbar {
  width: 100%;
  background-color: green;
  overflow-y: hidden;
  padding: 15px 0;
}

.navbar a {
  text-align: center;
  padding: 20px;
  color: white;
  text-decoration: none;
  font-size: 1.6rem;
}

.navbar a:hover {
  background-color: blue;
}

.home {
  background-color: coral}


@media screen and (max-width: 750px) {
  .navbar a {
    display: block;
  }
}
</style>