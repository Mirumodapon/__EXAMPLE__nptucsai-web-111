<template>
  <header>
    <div class="container">
      <img class="logo" src="https://www.dcard.tw/_next/static/media/logo.8b5bbef2.svg" />
      <form class="search-bar">
        <input type="text" placeholder="搜尋..." />
        <button class="btn">
          <img src="../assets/images/search-bar-btn.svg" />
        </button>
      </form>
      <button class="btn sign-btn">註冊 / 登入</button>
      <button class="btn more-opt"><span></span></button>
      <button class="btn down-app">下載 App</button>
    </div>
  </header>
</template>

<style scoped>
header {
  width: 100vw;
  height: 50px;

  background-color: #006aa6;
}
.container {
  width: 700px;
  max-width: 90vw;
  height: 50px;
  margin: auto;

  display: flex;
  align-items: center;
}
.logo {
  height: 30px;
}

.btn {
  border: 0;
}
.btn:focus {
  outline: 0;
}

.search-bar {
  display: flex;
  margin: 0 20px;
}

.search-bar input {
  border: 0;
  background-color: #00588a;
  font-size: 16px;
  border-radius: 5px 0 0 5px;
  padding: 0 5px;
  color: white;
}

.search-bar input::placeholder {
  color: #5c94b4;
}

.search-bar input:focus {
  outline: 0;
}

.search-bar button {
  background-color: #006aa6;
  padding: 5px 8px;
  border-radius: 0 5px 5px 0;
  border: 1px #00588a solid;
}

.search-bar button > img {
  width: 18px;
}

.sign-btn {
  background-color: transparent;
  color: white;
}

.more-opt {
  background-color: transparent;
}

.more-opt span {
  display: block;
  width: 0;
  height: 0;
  border-top: 8px solid white;
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-bottom: 0px solid white;
}

.down-app {
  background-color: #3397cf;
  border-radius: 10px;
  padding: 8px 15px;
  color: white;
  margin: 0 15px;
}

.down-app:hover {
  background-color: #5ab0db;
}
</style>
