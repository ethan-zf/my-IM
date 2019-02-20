<template>
  <div class="login-container">
    <div class="avatar">
      <img alt="Vue logo" src="../assets/logo.png" style="width: 100px">
      <div class="user-name">name</div>
    </div>
    <h1>{{ msg }}</h1>

  </div>
</template>

<script>
    export default {
        name: 'Login',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .login-container{
    padding: 16px;

  }
  .avatar {
    margin-top: 10px;
    text-align: center;
  }
  .user-name {
    text-align: center;
    font-size: 14px;
    font-weight: 600;
  }
  h3 {
    margin: 40px 0 0;
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
