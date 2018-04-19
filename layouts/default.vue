<template>
  <div style="height: 100%;">
    <nuxt/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:400,600%7CZeyada&subset=cyrillic');

#__nuxt, #__layout {
  height: 100%;
}

html {
  line-height: 1.15;
  -webkit-text-size-adjust: 100%;
}

body {
  margin: 0;
}

a {
  background-color: transparent;
}
html, body {
  height: 100%;
  font-family: 'Open Sans', sans-serif;
  font-size: 1rem;
}
.heading {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.logo {
  color: #313131;
  font-size: 8rem;
  font-family: 'Zeyada', sans;
  line-height: .5;
  user-select: none;
}

.navigation {
  padding: 0;
  margin: 0;
  text-align: center;
}

.navigation__item {
  display: inline-block;
  list-style: none;
  margin-right: .7rem;
}

.navigation__link {
  text-decoration: none;
  color: #a2a4b3;
  transition: .5s;
  font-weight: 700;
  text-transform: uppercase;
  font-size: .7rem;
  letter-spacing: .15rem;
}

.navigation__link:hover {
  color: #777884;
}
</style>
