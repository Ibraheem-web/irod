---
title: "Adversusはウェブベースのダイヤラーと実用的なCRMソリューションです"
date: 2020-04-18T10:07:21+06:00
# post image
image: "images/blog/post-6.jpg"
# post type (regular/featured)
type: "regluar"
# meta description
description: "これはメタディスクリプションです"
# post draft
draft: false
---


#### 見出し 例

以下は見出しの例です。この見出しは、markdownify のルールに従って使用できます。たとえば、見出し 1 には `#` を使用し、見出し 6 には `######` を使用します。

# 見出し 1 
<br>

## 見出し 2 

<br>

### 見出し 3 

<br>

#### 見出し 4 

<br>

##### 見出し 5 

<br>

###### 見出し 6


<hr>

##### 強調

強調 (斜体) には *アスタリスク* または _アンダースコア_ を使用します。

強い強調 (太字) には **アスタリスク** または __アンダースコア__ を使用します。

**アスタリスクと _アンダースコア_** を組み合わせた強調。

取り消し線には 2 つのチルダを使用します。~~これは削除します。~~

<hr>

##### リンク
[私はインラインスタイルのリンクです](https://www.google.com)

[私はタイトル付きのインラインスタイルのリンクです](https://www.google.com "Google's Homepage")

[私は参照形式のリンクです][Arbitrary case-insensitive reference text]

[私はリポジトリファイルへの相対参照です](../blob/master/LICENSE)

[参照形式のリンク定義には数字を使用できる][1]

または空白のままにして [リンクテキスト自体].

URL および山括弧内の URL は自動的にリンクに変換されます。
http://www.example.com または <http://www.example.com>、場合によっては
example.com (ただし、たとえば Github ではそうではありません)。

参照リンクが後で続くことを示すテキスト。

[任意の大文字と小文字を区別しない参照テキスト]: https://www.themefisher.com
[1]: https://gethugothemes.com
[リンク テキスト自体]: https://www.getjekyllthemes.com

<hr>

##### 段落

Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam nihil enim maxime corporis cumque totam aliquid nam sint inventore optio modi neque laborum officiis necessitatibus, facilis placeat pariatur! Voluptatem, sed harum pariatur adipisci voluptates voluptatum cumque, porro sint minima similique magni perferendis fuga! Optio vel ipsum excepturi tempore reiciendis id quidem? Vel in, doloribus debitis nesciunt fugit sequi magnam accusantium modi neque quis, vitae velit, pariatur harum autem a! Velit impedit atque maiores animi possimus asperiores natus repellendus excepturi sint architecto eligendi non, omnis nihil. Facilis, doloremque illum. Fugit optio laborum minus debitis natus illo perspiciatis corporis voluptatum rerum laboriosam.

<hr>

##### 順序付きリスト

1. リスト項目
2. リスト項目
3. リスト項目
4. リスト項目
5. リスト項目

<hr>

##### 順序なしリスト

* リスト項目
* リスト項目
* リスト項目
* リスト項目
* リスト項目

<hr>

##### コードと構文の強調表示

インライン `コード` には `バックティック` が付きます。

```javascript
var s = "JavaScript 構文の強調表示";
alert(s);
```
 
```python
s = "Python 構文の強調表示"
print s
```

<hr>

##### 引用ブロック

> これはblockquoteの例です。

<hr>

##### インライン HTML

Markdown で生の HTML を使用することもできます。ほとんどの場合、うまく機能します。

<dl>
<dt>定義リスト</dt>
<dd>時々使用されるものです。</dd>

<dt>HTML での Markdown</dt>
<dd>あまりうまく機能しません。HTML <em>タグ</em> を使用してください。</dd>
</dl>


<hr>

##### テーブル

コロンを使用して列を揃えることができます。

| 表 | は | かっこいい |
| ------------- |:-------------:| -----:|
| 列 3 は | 右揃え | $1600 |
| 列 2 は | 中央揃え | $12 |
| ゼブラ ストライプは | きれい | $1 |

各ヘッダー セルを区切るには、少なくとも 3 つのダッシュが必要です。

外側のパイプ (|) はオプションで、生の Markdown をきれいに並べる必要はありません。インライン Markdown を使用することもできます。

Markdown | 少ない | きれい
--- | --- | ---
*それでも* | `renders` | **きれいに**
1 | 2 | 3

<hr>

##### 画像

![画像](../../images/blog/post-6.jpg)

<hr>

##### Youtubeビデオ

{{< youtube C0DPdy98e4c >}}