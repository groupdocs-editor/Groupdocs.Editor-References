---
title: "FontEmbeddingOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "フォント埋め込みオプションは、出力 WordProcessing ドキュメントに埋め込むフォントリソースを制御します"
type: docs
weight: 17
url: /ja/nodejs-java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

フォント埋め込みオプションは、埋め込むフォントリソースを制御します
出力 WordProcessing ドキュメント


*** ** * ** ***

フォント埋め込みオプションは、ドキュメントの保存時（中間の EditableDocument から出力 WordProcessing 形式へ）に適用されます。この列挙体は WordProcessingSaveOptions のプロパティとして含まれ、そこから使用されます

<br />


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | EditableDocument からも、またそれ以外からもフォントリソースを埋め込まないでください |
システムから。
|
|  | [EmbedAll](#EmbedAll) | 入力 EditableDocument のドキュメント内容を解析し、使用されているすべてのフォントを見つけます |
そしてそれらを出力 WordProcessing ドキュメントに埋め込みます。
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) と同等ですが、これらのフォントは除外します、 |
OS によってシステムフォントとみなされるもの
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


EditableDocument からも、またそれ以外からもフォントリソースを埋め込まないでください
システム。デフォルト値。


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


入力 EditableDocument のドキュメント内容を解析し、使用されているすべてのフォントを見つけます
そしてそれらを出力 WordProcessing ドキュメントに埋め込みます。まず最初に
GroupDocs.Editor は EditableDocument 内のフォントリソースからフォントを取得します。
それらが不足または欠如している場合、GroupDocs.Editor はフォントを取得します
OS から取得します。


*** ** * ** ***

まず、GroupDocs.Editor は EditableDocument の内容を解析し、使用されているすべてのフォントのリストを作成します。その後、これらのフォントは EditableDocument のフォントリソース内で検索されます。EditableDocument にドキュメント内容に関与しないフォントリソースが含まれている場合、それらは無視されます。ドキュメント内容で使用されているフォントで、EditableDocument に対応するフォントリソースが存在しない場合、GroupDocs.Editor は OS でそれらを探します。このオプションは、Microsoft Word 2007 以降でサブオプションをすべてオフにした\"Embed fonts in the file\"オプションに似ています

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


[EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) と同等ですが、これらのフォントは除外します、
OS によってシステムフォントとみなされるもの


*** ** * ** ***

MS Windows にはシステムフォントという概念があり、これは Windows 自体が最も基本的に使用するフォントです。このオプションを使用すると、GroupDocs.Editor は [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) のケースと同様に動作しますが、最終的に取得したフォントのセットを確認し、OS によってシステムフォントとみなされるものを除外します。このオプションは、Microsoft Word 2007 以降の\"Embed fonts in the file\" + \"Do not embed common system fonts\"オプションに似ています

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
