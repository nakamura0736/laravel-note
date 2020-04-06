# laravel-note


### Authentication(認証機能)作成

以下は、Laravel最新バージョンでは仕様出来ない。チュートリアルなどでこの方法が出てきてもやってはいけない！
```
php artisan make:auth
```

代わりに以下を実践

```
composer require laravel/ui --dev
php artisan ui vue --auth
```

実行結果は成功だが、以下のような「やっといてね！」的なメッセージがでる。
```
Please run "npm install && npm run dev" to compile your fresh scaffolding.
```
これをやらないとログイン画面などでCSSが適用されないようです。素直にメッセージからコピって実行。
```
npm install && npm run dev
```
参考URL
https://qiita.com/kusumoto-t/items/fc6ef3f5bf1dbe5dc579
