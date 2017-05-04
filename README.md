# README

ReactとRailsを組み合わせて使う場合のサンプルです。Webpackを利用し、react-railsやWebpackerは使いません。

# Memo

ベースは http://techlife.cookpad.com/entry/2016/07/27/101015 の記事を参考にさせて頂きました。

## 違い

- npm install時にbabel-coreも実施(エラーが出て必要だと表示されたので)

```
npm install -D webpack babel-loader babel-preset-es2015 babel-preset-react

```

- webpack.config.jsの中身
    - 相対パス指定で怒られたので、https://github.com/shakacode/react-webpack-rails-tutorial を参考に改変

