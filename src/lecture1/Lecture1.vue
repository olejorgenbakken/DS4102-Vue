<template>
  <main>
    <Hero msg="Welcome comrade" brief="A showcase of icons" />
    <PersonList title="People"></PersonList>
  </main>
</template>

<script>
import Hero from "./components/Hero";
import PersonList from "./components/people/PersonList";
export default {
  name: "Lecture1",
  components: {
    Hero,
    PersonList
  }
};
</script>

<style scoped>
main {
  background: linear-gradient(0deg, rgb(0, 0, 0), rgb(61, 0, 0));
}
</style>