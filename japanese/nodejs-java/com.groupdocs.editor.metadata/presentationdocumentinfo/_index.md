---
title: "PresentationDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "プレゼンテーションドキュメントのメタデータを表します"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

プレゼンテーションドキュメントのメタデータを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | このプレゼンテーション文書の形式を返します |
|
|  | [getPageCount()](#getPageCount--) | このプレゼンテーション文書のスライド数を返します |
|
|  | [getSize()](#getSize--) | このプレゼンテーション文書のバイト単位のサイズを返します |
|
|  | [isEncrypted()](#isEncrypted--) | この特定のプレゼンテーション ドキュメントが暗号化されており、開く際にパスワードが必要かどうかを示します |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | 選択されたスライドのプレビューを SVG 画像の形式で生成し、返します |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


このプレゼンテーション文書の形式を返します


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


このプレゼンテーション文書のスライド数を返します


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


このプレゼンテーション文書のバイト単位のサイズを返します


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


この特定のプレゼンテーション ドキュメントが暗号化されており、開く際にパスワードが必要かどうかを示します


**Returns:**
ブール
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


選択されたスライドのプレビューを SVG 画像の形式で生成し、返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | slideIndex | int | 目的のスライドの 0 ベースインデックス。0 未満にすることはできず、このプレゼンテーションのスライド数を超えることもできません。 |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

