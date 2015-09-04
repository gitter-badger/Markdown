#見出し1

[![Join the chat at https://gitter.im/shotahirama/Markdown](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/shotahirama/Markdown?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
\#見出し1

---
##見出し2
\##見出し2

---
###見出し3
\###見出し3

---
スペース2つを行末にいれると改行できる

---
`コード挿入`  
\` バッククォーテーションで囲む \`  
あるいは行頭にスペース4つ

---
\`\`\`のあとに言語を書くことで、syntax highlightされる

    ```python
    class Hoge(object):
      def __init__(self):
        pass
      def update(self):
        print 'update'
      def strputs(self, str):
        print str
    ```
###⇓
```python
class Hoge(object):
  def __init__(self):
    pass
  def update(self):
    print 'update'
  def strputs(self, str):
    print str
```

---
>引用

\>引用  

>引用
>>ネストも可能

\>>ネスト

---
- 箇条書き

\- 箇条書き(-のあとにスペース)

---
テーブル

|a table|b table|c table|
|---|---|---|
|a1|b1|c1|
|a2|b2|c2|
|a3|b3|c3|

/|a table   |b table    |c table    |  
|---        |---        |---        |  
|a1         |b1         |c1         |  
|a2         |b2         |c2         |  
|a3         |b3         |c3         |

|a table|b table|c table|
|:---   |:---:  |---:   |
|a1     |b1     |c1     |
|a2     |b2     |c2     |
|a3     |b3     |c3     |

/|a table|b table|c table|  
|:---   |:---:  |---:   |  
|a1     |b1     |c1     |  
|a2     |b2     |c2     |  
|a3     |b3     |c3     |  
コロンを付けることによって寄らせることができる

---

リンク

[Markdown](https://github.com/shotahirama/Markdown)  
\[Markdown](https://github.com/shotahirama/Markdown)

[Markdown](https://github.com/shotahirama/Markdown "Markdown")  
\[Markdown](https://github.com/shotahirama/Markdown "Markdown")

()の中に"文字"を入れるとそれがタイトルになる
