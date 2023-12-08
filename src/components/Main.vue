<template>
  <div class="header">
    <img src="https://www.github.com/ilasdavide2011.png" width="150" height="150"/>
    <h1>@Dissiporio</h1>
  </div>
  <ul>
    <li>
      <a href="mailto:dissiporio@gmail.com">dissiporio@gmail.com</a>
    </li>
    <li>
      <a href="https://www.github.com/ilasdavide2011">Github</a>
    </li>
    <li>
      <a href="https://twitter.com/IlasDavide">Twitter(X)</a>
    </li>
  </ul>
</template>

<style scoped>
body {
  margin: 0px;
}
.header img{
  border-radius: 100px;
  border: 1px solid #fff
}
.header h1 {
  border-radius: 1em;
  background: #000a;
  color: #fff;
  border: 1px solid #fffa;
  padding: 0.3em 0.6em;
}

.header {
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: "Open Sans", sans-serif;
}
ul {
  box-sizing: border-box;
  list-style: none;
  padding: 1em;
  margin: 2em;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}
ul li {
  background: #000;
  border-radius: 10em;
  padding: 1em;
  margin: 1.4em 0;
  font-family: "Open Sans", sans-serif;
  width: 240px;
}

ul li a {
  text-decoration: none;
  color: #fff;
  font-size: 20;
}
</style>
