
# verify-youtube-api

## get started

必要なパッケージの取得。

```
$ npm install
```

続いて、必要な認証情報を取得する。具体的には `client_secret.json` という認証情報を記載した JSON ファイル。

これは、Google API コンソールでの操作が必要になる。

JSON を取得できたら、ファイル名を `client_secret.json` として `quickstart.js` と同じ階層に置く。

そこまで準備できたら、Node.js で `quickstart.js` を実行する。

```
$ node quickstart.js
```

途中、コマンドライン上で認証のためにこの URL を開いてキーを取得しろ的な感じのが出るので、ブラウザでアクセス＋認証許可を行い、キーをコマンドラインに貼り付けて Enter する。

認証が通ると、ユーザーのホームに `~/.credentials` というディレクトリが掘られて、そこにトークンの情報が自動的に出力される。また、認証を通したユーザーの情報を API を通じて取得し、その結果をコンソール上に出力している。


