<template>
  <div class="about" role="main">
    <div class="about-header">
      <img src="../assets/about.png" alt="about" class="about-img" />
      <p class="about-header-text">
        My name is <b>Zach Toben</b>. I'm a software developer located in Des
        Moines, Iowa.
      </p>
    </div>
    <p>
      <b>Toben Software</b> provides a broad range of software contracting and
      consulting services.
    </p>
    <p>
      I have a background in building and maintaining large scale web
      applications. I am experienced in designing clean and powerful user
      experiences, creating reliable APIs, and working with cloud
      infrastructure. Please contact me for additional information and rates.
    </p>
  </div>
</template>

<style lang="scss">
.about {
  min-width: 200px;
  max-width: 500px;
  width: 80%;

  .about-header {
    display: inline-flex;
    align-items: center;

    .about-header-text {
      padding-left: 20px;
    }
  }

  .about-img {
    max-width: 212px;
    min-width: 75px;
    width: 25%;
    border-radius: 50%;
  }
}
</style>
