<template>
  <div class="app-container">
    <p class="warn-content">
      This is the guide page
    </p>
    <el-button icon="el-icon-question" type="primary" @click.prevent.stop="guide">Show Guide</el-button>
  </div>
</template>

<script>
//import * as Driver from 'driver.js' // import driver.js
import 'driver.js/dist/driver.min.css' // import driver.js css
import steps from './defineSteps'

if (process.browser) {
var Driver= require('driver.js')
}
export default {
  
  name: 'Guide',
  data() {
    return {
      driver: null
    }
  },
  mounted() {
    this.driver = new Driver()
  },
  methods: {
    guide() {
      this.driver.defineSteps(steps)
      this.driver.start()
    }
  }
}
</script>
