<template>
  <div class="about">
    <h2>About the app</h2>
    <p class="about-text">
      Welcome to my personal task management app, I designed this to streamline
      my daily life, and learn Vue lol. Whether you're a busy professional, a
      student juggling assignments, or simply someone looking to boost
      productivity, this app provides a user-friendly interface and powerful
      features. Say goodbye to the chaos of scattered to-do lists and embrace a
      more organized and focused life. Cheers🎉
    </p>
  </div>
</template>

<style>
.about {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: start;
  padding-left: 8px;
  padding-right: 8px;
  gap: 15px;
}

.about-text {
  font-size: 16px;
  text-align: center;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding-left: 15%;
    padding-right: 15%;
  }
  .about-text {
    font-size: 18px;
    text-align: center;
  }
}
</style>
