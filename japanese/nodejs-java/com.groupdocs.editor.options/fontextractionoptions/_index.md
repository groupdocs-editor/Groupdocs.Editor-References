---
title: "FontExtractionOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "フォント抽出オプションは、どのフォントを抽出し、どこから抽出するかを制御します"
type: docs
weight: 18
url: /ja/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

フォント抽出オプションは、どのフォントを抽出し、どこから抽出するかを制御します
どこから

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NotExtract](#NotExtract) | ドキュメントからも |
システムから。
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | 入力された Word に埋め込まれたすべてのフォントリソースを抽出します |
ドキュメントから、カスタムかシステムかに関わらず抽出します。
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | カスタム（システムではない）埋め込みフォントリソースのみを抽出します |
システム)
|
|  | [ExtractAll](#ExtractAll) | 入力された WordProcessing で使用されているすべてのフォントを抽出しようとします |
ドキュメントから、システムフォントを含めて抽出します。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


ドキュメントからも
システム。デフォルト値。


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


入力された Word に埋め込まれたすべてのフォントリソースを抽出します
ドキュメントから、カスタムかシステムかに関わらず抽出します。


*** ** * ** ***

Converter は、入力の WordProcessing ドキュメントに埋め込まれたすべての 100% フォントリソースを検出して抽出しますが、システムフォントかカスタムフォントかは判別しません。また、Windows レジストリやシステムフォルダーには一切触れません。

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


カスタム（システムではない）埋め込みフォントリソースのみを抽出します
システム)


*** ** * ** ***

Converter はすべての埋め込みフォントリソースを検出して抽出し、これらのフォントがシステムフォントかどうかを判定しようとします。そのために、Converter は Windows レジストリとシステムフォルダーを使用してすべてのシステムフォントの一覧を取得し、その一覧を埋め込みフォントの集合と比較します。その結果、システムに存在しない埋め込みフォントのサブセットのみが返されます。

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


入力された WordProcessing で使用されているすべてのフォントを抽出しようとします
ドキュメントから、システムフォントを含めて抽出します。


*** ** * ** ***

Converter は入力の WordProcessing ドキュメントを解析し、使用されているすべてのフォントを検出します。これらのフォントがすべて入力ドキュメントに埋め込まれている場合、Converter はそれらを抽出して返します。そうでなく、埋め込みフォントのコレクションがドキュメントで使用されているすべてのフォントをカバーしていない、または空の場合、Converter は Windows レジストリとシステムフォルダーを使用してシステムからこれらのフォントリソースを抽出しようとします。

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
