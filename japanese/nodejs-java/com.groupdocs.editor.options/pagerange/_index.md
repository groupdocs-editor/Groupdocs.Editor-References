---
title: "PageRange"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "開いた境界または閉じた境界を持つページ範囲を 1 つカプセル化します。"
type: docs
weight: 27
url: /ja/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

開いた境界または閉じた境界を持つページ範囲を 1 つカプセル化します。デフォルトは\"完全にオープン\"で、すべての既存ページを含みます。ページ番号は 0 ではなく 1 から始まります。

<br />

*** ** * ** ***

特定のドキュメントに依存せず、任意のドキュメントのページ範囲を表すことができる、イミュータブルな構造体で、ページ範囲をカプセル化します。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [AllPages](#AllPages) | ドキュメントのすべての既存ページを表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | このページ範囲が開始する包括的な開始ページ番号です。 |
|
|  | [getEndNumber()](#getEndNumber--) | このページ範囲が続く排他的な終了ページ番号で、ここで終了します。 |
|
|  | [getCount()](#getCount--) | 範囲内のページ番号です。 |
|
|  | [isDefault()](#isDefault--) | このインスタンスがデフォルトの\"完全にオープン\"ページ範囲を表すかどうかを示します。 |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | この PageRange インスタンスが指定されたものと等しいかどうかを検出します。 |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | 最初のページから開始し、指定されたページ数を持つページ範囲を作成します |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | 指定されたページ番号から開始し、文書の末尾まで続くページ範囲を作成します |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | 指定されたページ番号から開始し、指定されたページ数、またはページ数無制限（末尾まで）を持つページ範囲を作成します |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | 指定されたページ番号（含む）から開始し、指定されたページ番号（除く）まで続くページ範囲を作成します |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


文書のすべての既存ページを表します。デフォルト値です。


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


このページ範囲が開始する包含的開始ページ番号です。1 の場合、ページ範囲は文書の最初のページから開始します


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


このページ範囲が終了する除外的終了ページ番号です。0 の場合、ページ範囲は文書の末尾まで広がります


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


範囲内のページ数です。0 の場合、ページ範囲は文書の末尾まで広がり、ページ数に関係なく含まれます


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


このインスタンスがデフォルトの \"fully open\" ページ範囲を表すかどうかを示します。つまり、文書のすべてのページで構成されます


**Returns:**
ブール
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


この PageRange インスタンスが指定されたものと等しいかどうかを検出します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | 等価性をチェックする他の PageRange インスタンス |
|

**Returns:**
boolean - true は等しい; false は等しくない

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


最初のページから開始し、指定されたページ数を持つページ範囲を作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageCount | int | ページ数。0 より大きい必要があります |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


指定されたページ番号から開始し、文書の末尾まで続くページ範囲を作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | startPageNumber | int | ページ範囲が開始するページ番号（含む）。ページ番号は 1 から始まり、0 より大きい必要があります |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


指定されたページ番号から開始し、指定されたページ数、またはページ数無制限（末尾まで）を持つページ範囲を作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | startPageNumber | int | ページ範囲が開始するページ番号（含む）。ページ番号は 1 から始まり、0 より大きい必要があります |
|
|  | pageCount | int | ページ数。0 より大きい必要があります。0 の場合、文書の末尾までのすべてのページを意味します |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


指定されたページ番号（含む）から開始し、指定されたページ番号（除く）まで続くページ範囲を作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | startPageNumber | int | ページ範囲が開始するページ番号（含む）。ページ番号は 1 から始まり、0 より大きい必要があります |
|
|  | endPageNumber | int | ページ範囲が続く終了ページ番号（除く）。ページ番号は 1 から始まり、0 より大きく、かつ startPageNumber より大きい必要があります |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
