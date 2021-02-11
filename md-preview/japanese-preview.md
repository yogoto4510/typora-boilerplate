---
title: MarkDown Preview
date: 2020-02-02
author: Yogoto
description: YAML front matter と呼ばれる、メタ情報を記入できるブロック
---

# Heading 1

Typora の テーマを開発するための Markdown です

Typora-Theme-Toolkit [^1] に含まれる lorem-ipsum.md をベースに自分用に作りかえています

## Heading 2

- 標準サポートのインライン記法  
  **強調**、_斜体_、`インラインブロック`、<u>下線</u>、~~取り消し線~~

- 設定から追加してサポートされる記法  
  $\LaTeX$、X^2^、H~2~O、==highlight==
  [絵文字表示](https://www.webfx.com/tools/emoji-cheat-sheet/)も可能： :cry:

- 画像について  
  []内に指定したワードは[alt 属性](https://developer.mozilla.org/ja/docs/Web/HTML/Element/img)になる
  キャプションは使用できない。どうしても入れたい場合は html 埋め込みになりそう

![img](https://i.imgur.com/RGLj3oV.jpg)

## その他の記法

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

> 祇園精舎の鐘の声、諸行無常の響あり。娑羅双樹の花の色、盛者必衰の理を顕す。奢れる人も久しからず、ただ春の夜の夢の如し。猛き者もつひには滅びぬ、偏に風の前の塵に同じ。
>
> > 遠く異朝を訪へば、秦の趙高、漢の王莽、梁の周伊、唐の禄山、これらは皆旧主先皇の政にも従はず、楽しみを極め、諫めをも思ひ入れず、天下の乱れん事を悟らずして、民間の憂ふる所を知らざりしかば、久しからずして、亡じにし者共なり。近く本朝を窺ふに、承平の将門、天慶の純友、康和の義親、平治の信頼、これらは猛き心も奢れる事も、皆とりどりにこそありしか、間近くは、六波羅の入道、前太政大臣平朝臣清盛公と申し人の有様、伝へ承るこそ心も詞も及ばれね。

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ | :-------------: | ------------: |
| col 3 is      | some wordy text |         $1600 |
| col 2 is      |    centered     |           $12 |
| zebra stripes |    are neat     |            $1 |

1. ordered list item 1.
2. ordered list item 2.
   - sub-unordered list item 1.
   - sub-unordered list item 2.
     - [x] something is DONE.
     - [ ] something is not TODO.

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>The *= Operator</h1>
    <p id="demo"></p>

    <script>
      var x = 10;
      x *= 5;
      document.getElementById("demo").innerHTML = x;
    </script>
  </body>
</html>
```

```mermaid
sequenceDiagram

title:Title
participant Alice
participant Bob
Alice->>John: Hello John, how are you?
loop Healthcheck
  John->>John: Fight against hypochondria
end
Note right of John: Rational thoughts <br/>prevail!
John-->>Alice: Great!
John->>Bob: How about you?
Bob-->>John: Jolly good!
```

[toc]

[^1]: https://github.com/typora/typora-theme-toolkit
