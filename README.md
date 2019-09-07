# go-mercari-scraper

## Description

go-mercari-scraper is scrape MERCARI.

![save JSON](https://github.com/go-numb/go-mercari-scraper/img/data.png)

## Installation

```
$ go get -u github.com/go-numb/go-mercari-scraper
```




## websocket/realtime
```golang

package main

import (
    github.com/go-numb/go-mercari-scraper
)

func main() {
    // 検索ワードのインプットを要求
    // キーワード取得後、MERCARIで検索後整形、JSONに保存
    merscraper.input()
}
```

## Author

[@_numbP](https://twitter.com/_numbP)

## License

[MIT](https://github.com/go-numb/go-mercari-scraper/blob/master/LICENSE)