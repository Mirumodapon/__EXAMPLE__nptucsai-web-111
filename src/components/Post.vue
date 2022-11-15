<template>
  <section class="post">
    <p class="classify">
      <img />
      <span>閒聊・1 小時前</span>
    </p>
    <h1 class="title">2022全國議員酒駕地圖</h1>
    <p class="content">
      前幾天整理資料做成excel 今天總算把它們視覺化了 從看完月蝕八點多做到一點，但是我覺得很值得
      以下是本屆議員選舉有酒駕相關紀錄，包括酒駕跟關說的候選人地圖，每一個人都會附上新聞或判決書
      也歡迎大家提出還有哪些我沒列出來的漏網之魚，查證屬實一定列上去
      如果有誤，也請通知我，我會以最快的速度更正並致上一百二十萬分的歉意
    </p>
    <p class="info">
      <img />
      <span>1000</span>
      <img />
      <span>1000</span>
    </p>
  </section>
</template>

<style scoped>
section {
  padding: 8px 25px;
  width: 85%;
  margin: auto;
  border-bottom: 1px solid #e9e9e9;
}

p {
  margin: 5px;
}
.classify {
  color: #999999;
  font-size: 14px;
}

.title {
  font-size: 20px;
  font-weight: normal;
  margin: 0;
}

.content {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  font-size: 16px;
}
</style>
