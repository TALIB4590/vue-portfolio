<template>
  <div id="app" v-cloak>
    <hero></hero>
    <about></about>
    <projects></projects>
    <skills></skills>
    <fork></fork>
    <contact></contact>
    <copyright></copyright>
    <repo-modal></repo-modal>
  </div>
</template>

<script>
import Hero from './components/Hero';
import About from './components/About';
import Projects from './components/Projects';
import Skills from './components/Skills';
import Contact from './components/Contact';
import Fork from './components/Fork';
import Copyright from './components/Copyright';
import RepoModal from './components/Projects/RepoModal';

export default {
  name: 'app',
  components: {
    Hero,
    About,
    Projects,
    Skills,
    Fork,
    Contact,
    Copyright,
    RepoModal,
  },
};
</script>

<style lang="scss">
#app {
  height: 100%;
  width: 100%;
  overflow: hidden;
}
</style>
