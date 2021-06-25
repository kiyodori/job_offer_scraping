# Job Offer Scraping

求人情報をスクレイピングし、CSV出力します。

## セットアップ

起動する。

```bash
$ ./vendor/bin/sail up -d
```

マイグレーションを実行する。

```bash
$ ./vendor/bin/sail artisan migrate
```

## 使う

求人情報をスクレイピングする。

```bash
$ ./vendor/bin/sail artisan scrape:mynavi
```
