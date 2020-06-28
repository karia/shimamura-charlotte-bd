<template>
  <div class="container">
    <div>
      <section class="single">
        <h2 class="subtitle">
          お知らせ
        </h2>

        <p>配布ワールドの下記の箇所について、訂正させていただきます。</p>

        <h3 class="sectiontitle">
          初期リスポーン位置の不具合について
        </h3>

        <div>
          <p>公開当初に配布していたセーブデータの初期リスポーン位置に誤りがございました。</p>
          <img src="errata/map.png" alt="map">
        </div>

        <h3 class="sectiontitle">
          タイトル  
        </h3>

        <div>
          <p>修正内容</p>
        </div>

        <h3 class="sectiontitle">
          タイトル
        </h3>

        <div>
          <p>修正内容</p>
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

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 60px;
  color: #210ba0;
  letter-spacing: 1px;
  padding-top: 30px;
  padding-bottom: 30px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-top: 100px;
  padding-bottom: 15px;
}

.sectiontitle {
  font-weight: 300;
  font-size: 30px;
  padding-top: 50px;
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
</style>
