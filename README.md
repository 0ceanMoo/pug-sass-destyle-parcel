# pug-sass-destyle-parcel

tailwindcssは、コンパイルに時間がかかって開発には使えなかった。

jitモードにすれば、使用しているクラスしかコンパイルしないらしいけど、
parcelを噛ませての設定方法が分からず。。。

これが解決するまでしばらく保留。
parcelを使わずに、webpackで自分で設定できれば良いんだけど、これも分からず。。。

```
git clone git@github.com:0ceanMoo/pug-sass-destyle-parcel.git my-coding
cd my-coding
yarn
```

```
yarn dev
//yarn build
```

ブラウザでlocalhost:1234にアクセスすれば確認できる。

src/pug/index.pugとsrc/sass/index.sassを編集していけばページが作れる
