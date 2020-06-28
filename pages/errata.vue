<template>
  <div class="container">
    <div>
      <section class="single">
        <h1 class="title">
          お知らせ
        </h1>

        <p>配布ワールドの下記の箇所に不具合がありましたので、訂正させていただきます。</p>

        <h2 class="subtitle">
          初期リスポーン位置の不具合について
        </h2>

        <section class="article">
          <div>
            <p>公開当初に配布していたバージョン1.16対応のセーブデータにおいて、プレイ開始時の初期位置（初期リスポーン位置）に誤りがございました。</p>
            <p>6月26日に更新した、最新の配布データ（charlotte-world-1.16.1-2020-06-26-15-55-04.zip）にて修正されております。</p>
          </div>

          <h3 class="sectiontitle">
            対応方法
          </h3>

          <div>
            <p>まだプレイ開始前の方：最新の配布データをダウンロードし、インストールしなおしてください。</p>
            <p>既にプレイ開始済みの方：以下の地図を参考に、正しい初期位置へ移動をお願いします。</p>
            <img src="errata/map.png" alt="map">
          </div>

          <h3 class="sectiontitle">
            【参考】ゲームモード別の移動方法
          </h3>

          <div>
            <p>・クリエイティブモードでプレイ中の方：通常飛行にて移動可能です</p>
            <p>・サバイバルモードに変更してプレイ中の方：島村建設本社ビル斜め向かい、ブティックFORESTからバーチャル赤羽エリア外へ飛び下りる事が可能です。落下ダメージはありません。</p>
          </div>
        </section>


        <h2 class="subtitle">
          タイトル  
        </h2>

        <section class="article">
          <div>
            <p>不具合の内容をここに書く</p>
          </div>

          <h3 class="sectiontitle">
           対応方法
          </h3>

          <div>
            <p>対応方法をここに書く（回避方法やテキストを読み替える内容など）</p>
          </div>
        </section>
      </section>

      <section class="backtotop">
        <nuxt-link to="/">
          トップページに戻る
        </nuxt-link>
      </section>

    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 60px;
  color: #210ba0;
  letter-spacing: 1px;
  padding-top: 10px;
  padding-bottom: 10px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-top: 15px;
  padding-bottom: 15px;
}

.sectiontitle {
  font-weight: 300;
  font-size: 30px;
  padding-top: 15px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
  padding-bottom: 15px;
}
#caution {
  border: medium solid red;
  padding: 20px;
  margin: 20px;
  font-size: 20px;
}
.article {
  border: 1px solid black;
}
</style>
