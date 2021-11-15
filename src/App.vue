<template>
  <div class="vue-tempalte">
    <!-- Navigation -->
    <nav class="navbar shadow bg-white rounded justify-content-between flex-nowrap flex-col fixed-bottom">
      <div class="container">
        <a class="navbar-brand float-left" href="https://rapidapi.com/blog/types-of-apis/">
           Devajohnson
        </a>
        <ul class="nav navbar-nav flex-row float-right">
          <li class="nav-item">
            <!-- <router-link class="nav-link pr-3" to="/login">Sign in</router-link> -->
            <router-link class="btn btn-outline-primary" to="/login">Sign in</router-link>
          </li>
          <li class="nav-item">
            <router-link class="btn btn-outline-primary" to="/">Sign up</router-link>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Main -->
    <div class="App">
      <div class="vertical-center">
        <div class="inner-block">
          <router-view />
        </div>
      </div>
    </div>
  </div>
</template>
