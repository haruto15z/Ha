


<template>
  <div class="container">
    <h1 class="heading">小型自動二輪・普通自動二輪</h1>
  </div>

  <div class="image-container">
    <div class="image-box">
      <img src="/img/xjr400.jpg" class="img-fluid bike-image" alt="中型バイク">
    </div>
    <div class="image-box">
      <img src="/img/kogata.jpg" class="img-fluid bike-image" alt="小型バイク">
    </div>
  </div>

  <div class="container">
    <p><strong>小型自動二輪車</strong></p>
    <p><strong>排気量</strong> 50cc～125ccのバイクです。</p>
    <p><strong>利点</strong> 小回りがきき、街乗りに適しています。</p>
    <p><strong>免許</strong> 免許は「普通自動二輪車免許」で取得できます。</p>
    
    <p><strong>普通自動二輪車</strong></p>
    <p><strong>排気量</strong> 126cc～400ccのバイクです。</p>
    <p><strong>利点</strong> 高速道路にも乗れるので、長距離移動にも適しています。</p>
    <p><strong>免許</strong> こちらも「普通自動二輪車免許」で乗れますが、上限が400ccまでです。</p>
    
    <p>要するに、排気量が小型は125cc以下、普通は126cc～400ccの範囲ということです。</p>

    <h2><a href="https://ha-trnb--54095--d20a0a75.local-credentialless.webcontainer.io/example_bike5" target="_blank" class="back-link">元のサイトに戻る</a></h2>
  </div>
</template>

<script>
export default {
  name: 'SmallAndStandardBikes'
};
</script>

<style scoped>
/* 見出しの装飾 */
.heading {
  text-align: center;
  font-weight: bold;
  color: #333;
  font-size: 2.5em;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

/* 画像のスタイル */
.image-container {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin: 20px 0;
}

.image-box {
  flex: 1;
  text-align: center;
}

.bike-image {
  width: 100%;
  height: auto;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.bike-image:hover {
  transform: scale(1.05); /* ホバー時に画像が少し大きくなる */
}

/* テキストのスタイル */
.container p {
  font-size: 1.2em;
  line-height: 1.6;
  color: #555;
  margin: 10px 0;
}

strong {
  font-weight: bold;
  color: #333;
}

h2 {
  font-size: 1.5em;
  text-align: center;
  margin-top: 20px;
}

a.back-link {
  color: #364e96;
  text-decoration: none;
}

a.back-link:hover {
  text-decoration: underline;
  color: #2a3b78;
}

/* スマホやタブレット向けのレスポンシブデザイン */
@media (max-width: 768px) {
  .heading {
    font-size: 2em;
  }

  .container p {
    font-size: 1em;
  }

  .image-container {
    flex-direction: column;
    gap: 10px;
  }

  .bike-image {
    max-width: 90%;
  }
}

@media (max-width: 480px) {
  .heading {
    font-size: 1.5em;
  }

  .container p {
    font-size: 0.9em;
  }
}
</style>