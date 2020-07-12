<template>
  <div class="container">
    <div>
      <section class="single">
        <h1 class="update-title">
          ハニスト2周年記念アップデート!
        </h1>

        <p>ハニーストラップ2周年を記念して「シャルと羊の世界2020」のアップデート版を配布します！</p>

        <p><a
          href="charlotte-world-1.16.1-2020-06-26-15-55-04.zip"
          class="button--green"
        >
          バージョン1.16.1対応データ　ダウンロード（78MB）
        </a></p>

        <div>
          （この配布ワールドで遊ぶにはMinecraft Java Editionが必要です）
        </div>

        <h2 class="update-subtitle">
          お祭り会場！
        </h2>

        <img src="/hnst2nd/yagura.jpg">
        <div>
           バーチャル赤羽のアーケードを抜けた先（社員寮近く）にお祭り会場ができました。
        </div>

        <h2 class="update-subtitle">
          新たな壁画！
        </h2>

        <img src="/hnst2nd/wallpainting.jpg">
        <div>
          歌ってみた動画「<a href="https://youtu.be/BhHSMrp8IMY">たしかなこと</a>」より、ハニスト4人のイラストを壁画（356×200ブロック）にしました。
        </div>

        <h2 class="update-subtitle">
          お祭り会場および壁画へのご案内
        </h2>

        <div>
          <img src="/hnst2nd/akabane-map.jpg">
        </div>
        <div>
          <img src="/hnst2nd/festival-guide.jpg">
        </div>
        <div>
          お祭り会場および壁画へはコチラのガイドを参考に移動してね！
        </div>

        <h3 class="sectiontitle">
          その他の更新内容
        </h3>

        <div>
          一部ゲームエリアにおいて、アイテムの数が減っても自動的に元に戻るようになりました。
        </div>

        <div>
          既知の不具合を修正しました。<a href="/errata">詳しくはお知らせのページを参照してください。</a>
        </div>
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

.update-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 42px;
  color: #210ba0;
  letter-spacing: 2px;
  padding-top: 30px;
  padding-bottom: 30px;
}

.update-subtitle {
  font-weight: 300;
  font-size: 38px;
  color: #526488;
  word-spacing: 5px;
  padding-top: 50px;
  padding-bottom: 15px;
}

.sectiontitle {
  font-weight: 300;
  font-size: 24px;
  padding-top: 30px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
  padding-bottom: 15px;
}
.backtotop {
  padding-top: 30px;
  padding-bottom: 30px;
}
#caution {
  border: medium solid red;
  padding: 20px;
  margin: 20px;
  font-size: 20px;
}
</style>
