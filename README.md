# go-mercari-scraper

## Description

go-mercari-scraper is scrape MERCARI.

![save JSON](https://github.com/go-numb/go-mercari-scraper/blob/master/img/data.png)

## Installation

```
$ go get -u github.com/go-numb/go-mercari-scraper
```




## websocket/realtime
```golang

package main

import (
    "github.com/go-numb/go-mercari-scraper"
)

func main() {
    // 検索ワードのインプットを要求
    // キーワード取得後、MERCARIで検索後整形、JSONに保存

    // 検索商品が尽きるまでQuery?page=n アクセスをsleep(1sec)で行います
    merscraper.input()
}
```


設定等々調整してください
``` golang
const (
	DIR        = "./nosql/"
	MERCARIURL = "https://www.mercari.com/jp/search/?keyword="

	// url query page=n の設定
	// 1ページで120productsほど
	MAXPAGE = 100
)
```

## Author

[@_numbP](https://twitter.com/_numbP)

## License

[MIT](https://github.com/go-numb/go-mercari-scraper/blob/master/LICENSE)