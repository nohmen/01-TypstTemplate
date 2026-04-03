# 01-TypstTemplate

## テンプレートの使用方法

テンプレートを適用したいファイルに以下のプログラムを打ち込んでください。

```
#import "/01_report/report_template.typ": *
#show: cover.with(
)
```

### 注意事項

#### HEADING

`=`又は`"#heading()`を使った場合、`Heading`の番号が表示されません。あらかじめご了承ください。

### レイアウト変更時

`Heading`のレベルは以下の通りです。

- `#h1` &rarr; level 1
- `#h2` &rarr; level 2
- `#h3` &rarr; level 3