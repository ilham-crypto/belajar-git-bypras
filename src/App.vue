<template>
  <div id="app" class="container">
    <div class="row py-4">
      <project-3 />
    </div>
    <br /><br />
    <div>
      <project-cv />
    </div>
  </div>
</template>

<script>
import Project3 from "./components/Project3.vue";
import ProjectCv from "./components/ProjectCv.vue";
export default {
  name: "app",
  components: {
    Project3,
    ProjectCv,
  },
};
</script>