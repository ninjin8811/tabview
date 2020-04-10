<template>
  <div id="app">
    <tab-view></tab-view>
  </div>
</template>

<script>
import TabView from './components/TabView.vue'
import Tab from './components/Tab.vue'

export default {
  // name: 'App',
  components: {
    'tab-view': TabView,
    'tab-button': Tab
  }
}
</script>
