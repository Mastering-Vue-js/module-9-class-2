<script setup>
import {ref} from "vue";
import OurTeam from "./components/OurTeam.vue";

const persons = ref([
  {
    name: "Bonnie Green",
    position: "CEO",
    description:
      "Bonnie drives the technical strategy of the flowbite platform and brand.",
    avatar:
      "//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/bonnie-green.png",
  },
  {
    name: "John Due",
    position: "Web Developer",
    description:
      "Bonnie drives the technical strategy of the flowbite platform and brand.",
    avatar:
      "//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/joseph-mcfall.png",
  },
  {
    name: "Jack John",
    position: "Backend Developer",
    description:
      "Bonnie drives the technical strategy of the flowbite platform and brand.",
    avatar:
      "//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/michael-gouch.png",
  },
  {
    name: "Samuel Sammy",
    position: "CEO & Web Developer",
    description:
      "Bonnie drives the technical strategy of the flowbite platform and brand.",
    avatar:
      "//flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/sofia-mcguire.png",
  },
]);
</script>

<template>
  <OurTeam :persons="persons" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
