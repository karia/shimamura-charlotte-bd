<template>
  <div class="container">
    <div>
      <section id="caution">
        <p><strong>テストプレイにご協力してくださる皆様へ</strong></p>
        <p>このWebサイトは2020年6月25日0時に公開する予定です。解禁時間まではTwitterなど公の場所にURLを漏らさないよう、ご協力をお願いします！</p>
        <p></p><a href="https://forms.gle/Ax9ZKcrmkJmTASRX9">テストプレイの感想フォームはこちらから！</a></p>
      </section>

      <section class="single">
        <h2 class="subtitle">
          配布ワールドデータをマインクラフトに入れる方法
        </h2>

        <p>※複数人で遊びたい場合は、先に一度「シングルでの遊ぶ」の手順を完了したあと「マルチ（Minecraft Realms）で遊ぶ」の手順に進んでください。</p>

        <h3 class="sectiontitle">
          シングルで遊ぶ方法（OSがWindowsの場合）
        </h3>

        <div>
          <p>以下の手順ではシングルのワールドとしてデータをインポートします。完了するとシングルで遊べるようになります。</p>

          <p>(0) ダウンロードしたzipファイルを解凍し、中に「charlotte-world」というフォルダがあるのを確認する</p>
          <img src="windows/download-zip.png" alt="download-zip">

          <p>(1) マインクラフトを起動し、「設定」をクリック</p>
          <img src="windows/1.png" alt="1">

          <p>(2)「リソースパック」をクリック</p>
          <img src="windows/2.png" alt="2">

          <p>(3)「リソースパックフォルダーを開く」をクリックする（別ウインドウでフォルダを開きます）</p>
          <img src="windows/3.png" alt="3">

          <p>(4) １つ上のフォルダに戻るボタンを押す</p>
          <img src="windows/4.png" alt="4">

          <p>(5) 「saves」フォルダを開く</p>
          <img src="windows/5.png" alt="5">

          <p>(6) マインクラフトを一旦終了させる</p>

          <p>(7) 「charlotte-world」フォルダを「saves」フォルダ内にドラッグ＆ドロップ</p>
          <img src="windows/saves-folder.png" alt="saves">

          <p>(8) マインクラフトを再度起動し、タイトルから「シングルプレイ」を選択。一覧にある「charlotte-world」と書かれたワールドを起動</p>
          <img src="windows/select-world.png" alt="saves">
        </div>

        <h3 class="sectiontitle">
          シングルで遊ぶ方法（OSがmacの場合）
        </h3>

        <div>
          <p>(0) ダウンロードしたzipファイルを解凍し、中身の「world」フォルダを適当な名前に変更する</p>

          <p>(1) 画面左下の、「Finder」のボタンをクリック</p>
          <img src="mac/01.png" alt="01">

          <p>(2) 画面左上の「移動」をクリックしたあと、「option」キーを押すと、押している間だけ「ライブラリ」が表示されるので、「ライブラリ」をクリック</p>
          <img src="mac/02.png" alt="02">

          <p>(3) 「Application Support」をダブルクリック</p>
          <img src="mac/03.png" alt="03">

          <p>(4)「minecraft」をダブルクリック</p>
          <img src="mac/04.png" alt="04">

          <p>(5) 「saves」をダブルクリック</p>
          <img src="mac/05.png" alt="05">

          <p>(6) 解凍したフォルダ（charlotte-world）を「saves」のウィンドウにドラッグ＆ドロップ</p>
          <img src="mac/06.png" alt="06">

          <p>(7) マインクラフトを起動し、タイトルから「シングルプレイ」を選択。</p>

          <p>(8) 「ワールドを選択」の画面に配布ワールドが追加されているので、選択して起動！</p>
          <img src="mac/07.png" alt="07">
        </div>

        <h3 class="sectiontitle">
          マルチ（Minecraft Realms）で遊ぶ方法
        </h3>

        <div>
          <p>※先に「シングルで遊ぶ方法」を実行しておいてください！以下、シングルで遊ぶ方法が完了しているものとして進めます。</p>

          <p>(1) マインクラフトを起動し、「Minecraft Realms」をクリック</p>
          <img src="realms/1.png" alt="1">

          <p>(2)「クリックしてRealmsを作る」をクリック</p>
          <img src="realms/2.png" alt="2">

          <p>(3) Realmsの名前、Realmsの説明を入力（好きな名前を決めてください）</p>
          <img src="realms/3.png" alt="3">

          <p>(4) 一覧の画面に戻るので、作成したサーバーをクリックしたあと、「Realmsの設定」をクリック</p>
          <img src="realms/4.png" alt="4">

          <p>(5) 「ワールドのリセット」をクリック</p>
          <img src="realms/5.png" alt="5">

          <p>(6) 「ワールドをアップロード」をクリック</p>
          <img src="realms/6.png" alt="6">

          <p>(7) 自分が持っているシングルのワールドが表示されるので、インポートしたいワールドをクリックし、「アップロード」を選択</p>
          <img src="realms/7.png" alt="7">

          <p>(8) アップロードが完了したら「完了」をクリック</p>
          <img src="realms/8.png" alt="8">

          <p>(9) 一覧の画面に戻るので、作成したサーバーをクリックしたあと、「プレイ」をクリック</p>
          <img src="realms/9.png" alt="9">

          <p>これでプレイできます！</p>
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