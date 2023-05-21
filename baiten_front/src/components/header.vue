<template>
<header>
  <table>
    <tr>
      <td id="header-title"><router-link to="/">BAITEN</router-link></td>
      <td class="header-link" align="right"><router-link to="login">로그인</router-link></td>
    </tr>
  </table>
</header>
</template>

<script>
export default {
  name: 'header'
}
</script>

<style scoped>
header {
  width: 100%;
  font-size: 1rem;
  padding-top: 60px;
  padding-bottom: 30px;
}

header table {
  width: 100%;
  height: 100%;
  border-bottom: 1px solid grey;
  border-collapse: collapse;
	margin: 0 auto;
}

header table tr td {
  padding-bottom: 20px;
}

header table tr #header-title {
  font-size: 2.2rem;
	font-weight: 800;
	border: 0;
}

header table tr .header-link {
  font-size: 1.2rem;
}
</style>