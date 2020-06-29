<template>
  <div class="container">
    <div>
      <section class="single">
        <h1 class="eratta_title">
          お知らせ
        </h1>

        <p>配布ワールドの下記の箇所に不具合がありましたので、訂正させていただきます。</p>

        <h2 class="eratta_subtitle">
          初期リスポーン位置の不具合について
        </h2>

        <section class="eratta_article">
          <div>
            <p>公開当初に配布していたバージョン1.16対応のセーブデータにおいて、プレイ開始時の初期位置（初期リスポーン位置）に誤りがございました。</p>
            <p>6月26日に更新した、最新の配布データ（charlotte-world-1.16.1-2020-06-26-15-55-04.zip）にて修正されております。</p>
          </div>

          <h3 class="eratta_sectiontitle">
            対応方法
          </h3>

          <div>
            <p>まだプレイ開始前の方：最新の配布データをダウンロードし、インストールしなおしてください。</p>
            <p>既にプレイ開始済みの方：以下の地図を参考に、正しい初期位置へ移動をお願いします。</p>
            <img src="/errata/map.png" alt="map">
          </div>

          <h3 class="eratta_sectiontitle">
            【参考】ゲームモード別の移動方法
          </h3>

          <div>
            <p>・クリエイティブモードでプレイ中の方：通常飛行にて移動可能です</p>
            <p>・サバイバルモードに変更してプレイ中の方：島村建設本社ビル斜め向かい、ブティックFORESTからバーチャル赤羽エリア外へ飛び下りる事が可能です。落下ダメージはありません。</p>
          </div>
        </section>

        <h2 class="eratta_subtitle">
          バーチャル赤羽エリアの「赤羽の9冊の本の謎」について
        </h2>

        <section class="eratta_article">
          <div>
            <p>「赤羽の９冊の本の謎」の最後に本を収めるエリアにて、本の既読・未読などが正しく判断されるため、反応しないことがあります</p>
          </div>

          <h3 class="eratta_sectiontitle">
           対応方法（下記のいずれかの方法で回避できます）
          </h3>

          <div>
            <p>・9冊の本を入手する際に１冊入手後、チェスト裏のリセットボタンを押して、もう一冊本を手に入れておく</p>
            <p>・タルの手前のブロックを破壊して出てきたホッパーの中にある本をマウス中ボタン等複製して入れる（クリエイティブモード限定）</p>
          </div>
        </section>

        <h2 class="eratta_subtitle">
          バーチャル赤羽エリア「ミコシャルTNT処理班」の指示書について
        </h2>

        <section class="eratta_article">
          <div>
            <p>ミコシャルTNT処理班の解除指示書14Pにて、環境によって最後の一行が表示されない場合がある</p>
            <img src="/errata/tnt-book-incollect.png" alt="解除指示書">
          </div>

          <h3 class="eratta_sectiontitle">
           対応方法
          </h3>

          <div>
            <p>正しい内容はスクリーンショットを参照してください</p>
            <img src="/errata/tnt-book-collect.png" alt="解除指示書">
            <p><strong>ミニゲーム開始前にあらかじめ指示書のP14を確認するようにお願いします</strong></p>
          </div>
        </section>

        <h2 class="eratta_subtitle">
          バーチャル赤羽エリア「島村フラワーガーデン」前の地図について 
        </h2>

        <section class="eratta_article">
          <div>
            <p>黄9丁目エリア、島村フラワーガーデンの前の地図が消えていることがあります</p>
          </div>

          <h3 class="eratta_sectiontitle">
           対応方法
          </h3>

          <div>
            <p>黄9丁目の旗の上に浸食してきているツタを破壊すると地図が表示されるようになります</p>
            <img src="/errata/flower-garden-map-collect.jpg" alt="島村フラワーガーデン前">
          </div>
        </section>

        <h2 class="eratta_subtitle">
          看板の表示内容修正
        </h2>

        <section class="eratta_article">
          <div>
            <p>シャルロッ島案内所のしずえさんの看板で、島の評価を「星5つ」と言っているにもかかわらず「★★★★」と4個しか表示されていない場合がある（環境によって、表示される場合とされない場合がある）</p>
          </div>

          <h3 class="eratta_sectiontitle">
           対応方法
          </h3>

          <div>
            <p>下記のスクリーンショットが正しい表示となりますので、読み替えをお願いします。</p>
            <img src="/errata/charlotte-island-star.png" alt="シャルロッ島の評価">
            <p>※ワールドをプレイする上での支障はありません</p>
          </div>
        </section>

      </section>

        <h2 class="eratta_subtitle">
          バーチャル赤羽エリア「島村建設メディアビル」の表記について
        </h2>

        <section class="eratta_article">
          <div>
            <p>バーチャル赤羽エリア・島村建設メディアビルにある上層階用エレベーターの看板で「しまむーびー」表記になってしまっている箇所がある</p>
            <img src="/errata/shimamura-media-bldg-movie.jpg" alt="島村建設メディアビル">
          </div>

          <h3 class="eratta_sectiontitle">
           対応方法
          </h3>

          <div>
            <p>「しまむービー」（後ろ2文字がカタカナ）に読み替えをお願いします。</p>
            <p>※ワールドをプレイする上での支障はありません</p>
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

.eratta_title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 40px;
  color: #210ba0;
  letter-spacing: 1px;
  padding-top: 10px;
  padding-bottom: 10px;
}

.eratta_subtitle {
  font-weight: 300;
  font-size: 30px;
  color: #526488;
  word-spacing: 5px;
  padding-top: 15px;
  padding-bottom: 15px;
}

.eratta_sectiontitle {
  font-weight: 300;
  font-size: 26px;
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

.eratta_article {
  border: 1px solid black;
  padding: 15px;
  margin-bottom: 30px;
}
</style>
