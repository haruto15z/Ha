
<template>
  <div class="container">
    <h1 class="heading">大型自動二輪車</h1>
  </div>

  <div class="image-container">
    <div class="image-box">
      <img src="/img/Yamaha.jpg" class="img-fluid bike-image" alt="大型の写真">
    </div>
    <div class="image-box">
      <img src="/img/oogata.jpg" class="img-fluid bike-image" alt="大型の写真">
    </div>
  </div>

  <div class="container">
    <p><strong>排気量</strong> 400ccを超えるエンジンを持つバイク（400cc以上のバイクです。）</p>
    <p><strong>免許</strong> 運転するためには「大型自動二輪免許」の資格が必要です。</p>
    <p><strong>税金＆保険</strong> 自動車税が高く、維持費が高いです。</p>
    <p>普通自動二輪（中型・小型）と比べて、エンジンの力が強いため、加速や走行性能が優れておりバイク好きから人気があります。</p>

    <h2><a href="https://ha-trnb--54095--d20a0a75.local-credentialless.webcontainer.io/example_bike5" target="_blank" class="back-link">元のサイトに戻る</a></h2>
  </div>
</template>

<script>
export default {
  name: 'LargeMotorcycle'
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