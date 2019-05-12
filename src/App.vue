<template>
  <div id="app">
    <nav class="contianer">
      <div id="logo">
        <h2>
          <span>M</span>arket
        </h2>
      </div>
      <div id="search">
        <input type="text" placeholder="search">
      </div>
      <ul id="tool">
        <li>
          <a href="#" class="active">Login</a>
        </li>
        <li>
          <a href="#">creat account</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Market",
  components: {}
};
</script>

<style>
.contianer {
  padding-left: 10%;
  padding-right: 10%;
}
nav {
  width: 100%;
  background: #aaa;
  overflow: hidden;
  padding-bottom: 10px;
  padding-top: 10px;
  text-align: center;
}
nav #logo {
  float: left;
}
nav #logo h2 span {
  color: rgb(148, 117, 49);
}
nav #tool {
  float: right;
}
nav #tool li {
  float: left;
}
nav #tool li a {
  font-size: 16px;
  padding: 3px 7px;
  transition: 0.3s;
  border-radius: 3px;
}
nav #tool li a.active {
  color: rgb(148, 117, 49);
  border: 1px solid;
}
nav #tool li a:hover {
  background: rgb(148, 117, 49);
  color: #fff;
  border: none;
}
nav #search {
  display: inline-block;
  width: 40%;
  background:rgb(184, 181, 173);
  padding:3px;
  border:1px solid rgb(151, 151, 151);
  border-radius:3px;

}
nav #search input {
  width: 100%;
  height: 100%;
  border: none !important;
  outline: none !important;
  background:transparent;
  color:rgb(80, 70, 47);
  font-size:20px;
}
</style>
