<template>
  <q-page class="">
    <div
      class="hero bg-dark flex justify-center items-center q-gutter-x-xl"
      style="height: 100vh; width:auto;"
    >
      <div class="image">
        <a href=""
          ><q-img
            class="rounded-borders "
            spinner-color="white"
            src="../assets/Khashayar-Shomali.jpg"
            alt="Khashayar Shomali"
            style="width: 450px"
        /></a>
      </div>
      <div class="bio text-h4 text-white">
        <p style="width:550px; line-height: 4rem;">
          Howdy, I'm Khashayar Shomali Young Junior Front-End Developer Who Make This
          Tutorial for You to Help You Learn Quasar Framework by Simple
          Projects.
        </p>
        <q-btn @click="openGitHub" color="deep-orange" label="My Github Profile" class="q-px-xl q-py-md q-mt-lg text-h6"/>
      </div>
    </div>
    
  </q-page>
</template>

<script setup>
const openGitHub = () => {
  window.open("https://www.github.com/shomalikhashayar");
};
</script>
