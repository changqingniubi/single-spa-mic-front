<template>
  <div id="app">
     <router-link to="/">Home</router-link> |
     <router-link to="/about">About</router-link>
     <router-link to="/vue">加载vue应用</router-link>
      <router-view/>
     <!--子应用加载的位置-->
     <div id="vue"></div>
  </div>
</template>

<style>

</style>