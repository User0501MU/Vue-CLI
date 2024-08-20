参考先：https://yoshida-no-atama.com/java-vue-mysql/

Springboot、STS上でVue.jsを使う

本書②：Vueプロジェクトをディレクトリ内に格納する
Vue CLIをインストールする※Vue.jsを使うにはNode.jsのインストールが必要であった。


～～～～～～～～～～～～～～～～～～～～～～


コマンドプロンプトでVue CLI のバージョンを確認する
vue –versionではなくvue --version
@vue/cli 5.0.8

Vueプロジェクトを作成する
①vue create vue-sample
②キーボードの下矢印でカーソルを動かし、「Default ([ Vue 2] babel, eslint)」を選択します。Enterを押すとプロジェクトの作成が始まります。

個人的ミス※Cドライブのユーザーの直下に作成してしまったのでSTSのオブジェクトへ移動
　→STSのオブジェクトを右クリックしリフレッシュしたら表示された。

③コマンドプロンプトでvue-sample直下へ移動します。
C:\Users\任意user\Documents\workspace0701\sample_project\vue-sample
④移動したら、以下のコマンドを入力しlocalhost:8081」にアクセス
npm run serve
