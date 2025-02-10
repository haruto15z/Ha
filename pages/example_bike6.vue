<template>
  <div class="container">
    <h1 class="heading">原動機付自転車</h1>
  </div>

  <!-- 画像表示のセクション（横並び） -->
  <div class="container image-container">
    <div class="image-box">
      <img src="/img/gentuki.jpg" class="img-fluid hover-effect" alt="原付の画像">
    </div>
    <div class="image-box">
      <img src="/img/zitensya.jpg" class="img-fluid hover-effect" alt="自転車の画像">
    </div>
  </div>

  <!-- コンテンツ部分 -->
  <div class="container text-container">
    <p><strong>排気量:</strong> 50cc以下のエンジンを搭載しています。</p>
    <p><strong>速度制限:</strong> 時速30～60km程度が一般的</p>
    <p><strong>免許:</strong> 16歳以上で取得可能で、普通免許を所持していれば50cc以下の原動機付き自転車を運転できます。</p>
    <p><strong>税金＆保険:</strong> 自動車税が安く、維持費が比較的少ないのが特徴です。</p>
    <p>原動機付き自転車は、50cc以下のエンジンを搭載した二輪車で、軽便で手軽に移動手段として利用できるバイクです。</p>
  </div>

  <!-- リンクセクション -->
  <div class="container link-container">
    <h2><a href="https://ha-trnb--54095--d20a0a75.local-credentialless.webcontainer.io/example_bike5" target="_blank" class="back-link">元のサイトに戻る</a></h2>
  </div>
</template>

<style>
  /* グローバルスタイル */
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
  }

  .container {
    margin: 20px auto;
    padding: 20px;
    max-width: 1200px;
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .heading {
    font-size: 2.5em;
    text-align: center;
    margin-bottom: 20px;
    color: #333;
  }

  /* 画像横並びレイアウト */
  .image-container {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    margin-bottom: 20px;
  }

  .image-box {
    flex: 1;
    text-align: center;
  }

  .img-fluid {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    transition: transform 0.3s ease, box-shadow 0.3s ease; /* 画像の動きと影の効果 */
  }

  .img-fluid:hover {
    transform: scale(1.05); /* ホバー時に画像を拡大 */
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); /* ホバー時に影をつける */
  }

  .text-container {
    font-size: 1.2em;
    color: #555;
  }

  .text-container p {
    margin-bottom: 15px;
  }

  .text-container strong {
    color: #333;
  }

  .link-container {
    text-align: center;
    margin-top: 30px;
  }

  .back-link {
    font-size: 1.2em;
    color: #007bff;
    text-decoration: none;
  }

  .back-link:hover {
    text-decoration: underline;
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