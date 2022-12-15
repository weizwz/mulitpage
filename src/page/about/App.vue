<template>
  <div id="app">
    <p>this is about page</p>
    <div class="my">
      <div class="bg"></div>
      <div class="cover">
        <img src="../../assets/head.jpg" alt="">
      </div>
      <div class="info">
        <h1>weizwz</h1>
        <h2>Undergrad | Web Developer</h2>
        <h2>🔥 Tech Enthusiast 🔥</h2>
      </div>
      <p style="font-size: 14px;margin: 15px 0;">知之为知之，不知为不知</p>
      <div class="github">
        <el-link class="view" :underline="false" href="https://github.com/weizwz/" target="_blank">
          <svg height="16" aria-hidden="true" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true"
            class="octicon octicon-mark-github v-align-middle">
            <path fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z">
            </path>
          </svg>
          Follow
        </el-link>
        <div class="link">
          <p>email: <el-link :underline="false" href="weizwz@foxmail.com" target="_blank">weizwz@foxmail.com</el-link></p>
          <p>&nbsp;&nbsp;blog: <el-link :underline="false" href="http://weizwz.com" target="_blank">http://weizwz.com</el-link></p>
        </div>
      </div>
    </div>
    <p><a href="/">go to home</a></p>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.my {
  width: 320px;
  padding: 0 0 20px;
  margin: 0 auto;
  border: solid 1px #999;
  border-radius: 8px;
}

.bg {
  height: 120px;
  width: 100%;
  border-radius: 6px 6px 0 0;
  background: #1e9fff;
}
.cover {
  width: 120px;
  height: 120px;
  background: #fff;
  border-radius: 50%;
  overflow: hidden;
  margin: -60px auto 0;
  padding: 2px;
}
.cover > img {
  margin-top: 2px;
  width: 116px;
  height: 116px;
  border-radius: 50%;
}
.info>h2 {
  font-size: 14px;
  margin: 2px 0;
}
.view {
  width: 120px;
  margin: 0 auto;
  border: solid 2px #1e9fff;
  line-height: 30px;
  font-size: 14px;
  margin-bottom: 15px;
}
.view > .el-link--inner {
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: bold;
}
.view svg {
  margin-right: 6px;
  margin-top: -2px;
}
.link > p {
  padding-left: 80px;
  text-align: left;
  margin: 0 0 5px;
  font-size: 14px;
}
</style>
