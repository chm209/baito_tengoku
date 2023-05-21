<template>
  <router-view/>
</template>

<script>
</script>

<style>
/* 스크롤바 없애기 */
::-webkit-scrollbar {
    width: 0;
    background: transparent;
}

/* 스타일 초기화 */
a:hover {
    text-decoration: none;
    cursor: default;
}

a, a:active, a:after {
    text-decoration: none;
    cursor: default;
    color: #333333;
}

ul,li {
    margin:0;
    padding:0;
    list-style: none;
    display: inline;
}

html, body {
  margin: 0 auto;
  padding: 0;
  font-family: 'Noto Sans KR', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}

#app {
  width: 1130px;
  height: 100%;
  margin: 0 auto;
  padding: 0;
  background-color: white;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
