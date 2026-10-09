---
title: "MhtmlSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "集約された HTML ドキュメントの MHTML MIME カプセル化を生成および保存するためのカスタムオプションを指定できます。"
type: docs
weight: 26
url: /ja/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

MHTML（複数の HTML ドキュメントの MIME カプセル化）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | MHTML ドキュメントに含まれるリソース（画像、フォント、CSS）を参照するために CID（Content-ID）URL を使用するかどうかを指定します。 |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | MHTML ドキュメントに含まれるリソース（画像、フォント、CSS）を参照するために CID（Content-ID）URL を使用するかどうかを指定します。 |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | 組み込みおよびカスタムのドキュメントプロパティを MHTML にエクスポートするかどうかを指定します。 |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | 組み込みおよびカスタムのドキュメントプロパティを MHTML にエクスポートするかどうかを指定します。 |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | MHTML に言語情報がエクスポートされるかどうかを指定します。 |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | MHTML に言語情報がエクスポートされるかどうかを指定します。 |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


MHTML ドキュメントに含まれるリソース（画像、フォント、CSS）を参照するために CID (Content-ID) URL を使用するかどうかを指定します。デフォルト値は
false
.

<br />

*** ** * ** ***


デフォルトでは、MHTML ドキュメント内のリソースはファイル名（例: \"image.png\"）で参照され、MIME パートの \"Content-Location\" ヘッダーと照合されます。このオプションは代替手法を有効にし、リソースファイルへの参照を CID (Content-ID) URL（例: \"cid:image.png\"）として記述し、\"Content-ID\" ヘッダーと照合します。


理論的には、2 つの参照方法の間に違いはなく、どちらも任意のブラウザやメールエージェントで正常に動作するはずです。しかし実際には、一部のエージェントがファイル名でリソースを取得できないことがあります。ブラウザやメールエージェントが MTHML ドキュメントに含まれるリソースの読み込みを拒否する（画像が表示されない、CSS スタイルが読み込まれない）場合は、CID URL を使用してドキュメントをエクスポートしてみてください。

<br />



**Returns:**
ブール
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


MHTML ドキュメントに含まれるリソース（画像、フォント、CSS）を参照するために CID (Content-ID) URL を使用するかどうかを指定します。デフォルト値は
false
.

<br />

*** ** * ** ***


デフォルトでは、MHTML ドキュメント内のリソースはファイル名（例: \"image.png\"）で参照され、MIME パートの \"Content-Location\" ヘッダーと照合されます。このオプションは代替手法を有効にし、リソースファイルへの参照を CID (Content-ID) URL（例: \"cid:image.png\"）として記述し、\"Content-ID\" ヘッダーと照合します。


理論的には、2 つの参照方法の間に違いはなく、どちらも任意のブラウザやメールエージェントで正常に動作するはずです。しかし実際には、一部のエージェントがファイル名でリソースを取得できないことがあります。ブラウザやメールエージェントが MTHML ドキュメントに含まれるリソースの読み込みを拒否する（画像が表示されない、CSS スタイルが読み込まれない）場合は、CID URL を使用してドキュメントをエクスポートしてみてください。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


組み込みおよびカスタムのドキュメント プロパティを MHTML にエクスポートするかどうかを指定します。デフォルト値は
false
.


**Returns:**
ブール
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


組み込みおよびカスタムのドキュメント プロパティを MHTML にエクスポートするかどうかを指定します。デフォルト値は
false
.


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


言語情報が MHTML にエクスポートされるかどうかを指定します。デフォルト値は
false
.

<br />

*** ** * ** ***

このプロパティが true に設定されている場合、GroupDocs.Editor は言語を指定するドキュメント要素に lang HTML 属性を出力します。これは言語に関連するセマンティクスを保持するために必要になることがあります。

<br />



**Returns:**
ブール
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


言語情報が MHTML にエクスポートされるかどうかを指定します。デフォルト値は
false
.

<br />

*** ** * ** ***

このプロパティが true に設定されている場合、GroupDocs.Editor は言語を指定するドキュメント要素に lang HTML 属性を出力します。これは言語に関連するセマンティクスを保持するために必要になることがあります。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

