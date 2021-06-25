# Job Offer Scraping

求人情報をスクレイピングし、CSV出力します。

## セットアップ

起動します。

```bash
$ ./vendor/bin/sail up -d
```

マイグレーションを実行します。

```bash
$ ./vendor/bin/sail artisan migrate
```

## 使用

求人情報をスクレイピングします。

```bash
$ ./vendor/bin/sail artisan scrape:mynavi
```

`storage/app/mynavi_jobs.csv` にCSVが出力されます。
