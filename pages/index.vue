<template>
  <section class="main">
    <span class="title">Frontend Developer</span>
    <span class="name">Nazym <span class="bolder">Jumadilova</span></span>
    <div class="description">
      
      <p>Previously — 
        <a class="description__link" target="_blank" href="https://aviata.kz">Aviata</a>,
        <a class="description__link" target="_blank" href="https://bookingcontrolsolutions.com">BCS</a> and
        <a class="description__link" target="_blank" href="https://efly.kz">eFly</a>.
      </p>
      <p>
        See my 
        <a class="description__link" target="_blank" href="//github.com/rustcohlnikov">projects</a> or just
        <a class="description__link" target="_blank" href="//t.me/relerin">send me a message</a>.
      </p>
      <p class="small">
        Also known as
        <a class="description__link" target="_blank" href="//www.instagram.com/relerin/">photographer</a>, feminist and a book lover.
      </p>
    </div>
  </section>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style>
.title {
  color:#828282;
}

.title::first-letter {
  margin-left: .2em;
}
.name {
  font-size: 3rem;
  font-weight: 500;
  margin: 0;
  margin-bottom: 1rem;
}
.main {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: start;
  padding-left: 20vw;
}

.logo {
  z-index: 1;
  width: 85vh;
  position: fixed;
  left: 5vw;
}

.small {
  padding-top: .5rem;
  font-size: .8rem;
  color: #828282;
}

.description {
  z-index: 2;
}

.description__link {
  text-decoration: none;
  color: rgb(38, 158, 155);
  -webkit-transition: background-color 0.2s ease;
  -moz-transition: background-color 0.2s ease;
  -o-transition: background-color 0.2s ease;
  transition: background-color 0.2s ease;
}

.description__link:hover {
  background-color: rgba(38, 158, 155, .1);
  border: none;
}
</style>
