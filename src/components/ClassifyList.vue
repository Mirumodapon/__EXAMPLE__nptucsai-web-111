<template>
  <section class="border-list">
    <ul>
      <li>
        <img src="../assets/images/temp.svg" />
        <span>所有看板</span>
      </li>
      <li>
        <img src="../assets/images/temp.svg" />
        <span>即時熱門看板</span>
      </li>
      <li>
        <img src="../assets/images/temp.svg" />
        <span>好物研究室</span>
      </li>
      <li>
        <img src="../assets/images/temp.svg" />
        <span>創作者排行</span>
      </li>
      <li>
        <img src="../assets/images/temp.svg" />
        <span>遊戲專區</span>
      </li>
    </ul>
    <h1>Dcard 精選看板</h1>
    <ul>
      <li>
        <img src="../assets/images/temp.svg" />
        <span>工作</span>
      </li>
      <li>
        <img />
        <span>美食</span>
      </li>
      <li>
        <img />
        <span>旅遊</span>
      </li>
    </ul>
  </section>
</template>
<style scoped>
* {
  color: rgba(255, 255, 255, 0.75);
  font-size: 16px;
}

section > ul {
  list-style: none;
  padding: 0;
}

section > ul li {
  padding: 10px 0;
  display: flex;
  align-items: center;
}

section > ul img {
  width: 18px;
  vertical-align: middle;
  margin: 5px;
}

section > ul li:hover {
  background-color: #002133;
}

h1 {
  color: #59798b;
  font-family: inherit;
  font-size: 14px;
}
</style>
