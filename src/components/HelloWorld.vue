
<template>
  <div class="homepage" id="homepage">
    <h1>{{ mainTitle }}</h1>
    <p>
      This is the homepage of nyan_wiki
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>分类</h3>
    <ul>
      <li><a href="https://www.bilibili.com" target="_blank" rel="noopener">ACGN</a></li>
      <li><a href="https://www.hupu.com" target="_blank" rel="noopener">体育</a></li>
      <li><a href="https://www.baidu.com">娱乐</a></li>
      <li><a href="HelloWorld.vue">直播</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
    <ul>
      <label>
        <input type=text v-model="testInput" placeholder="怎么这么麻烦">
      </label>
    </ul>
    <h4>{{testInput}}</h4>
  </div>
</template>

<script>

export default {
  name: 'nyan_wiki',
  data() {
    return{
      mainTitle:"Nyan Wiki",
      testInput:"",
    }
  }

}



</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1 {
  margin: 10px 10px 0;
}
h3 {
  margin: 40px 0 0;
}
h4 {
  margin: 10px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
