---
title: "PresentationFormats"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "すべてのプレゼンテーション形式をカプセル化します。"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.editor.formats/presentationformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class PresentationFormats extends DocumentFormatBase
```

すべてのプレゼンテーション形式をカプセル化します。以下の形式が含まれます：
[Odp](../../com.groupdocs.editor.formats/presentationformats#Odp),
[Otp](../../com.groupdocs.editor.formats/presentationformats#Otp),
[Pot](../../com.groupdocs.editor.formats/presentationformats#Pot),
[Potm](../../com.groupdocs.editor.formats/presentationformats#Potm),
[Potx](../../com.groupdocs.editor.formats/presentationformats#Potx),
[Pps](../../com.groupdocs.editor.formats/presentationformats#Pps),
[Ppsm](../../com.groupdocs.editor.formats/presentationformats#Ppsm),
[Ppsx](../../com.groupdocs.editor.formats/presentationformats#Ppsx),
[Ppt](../../com.groupdocs.editor.formats/presentationformats#Ppt),
[Ppt95](../../com.groupdocs.editor.formats/presentationformats#Ppt95),
[Pptm](../../com.groupdocs.editor.formats/presentationformats#Pptm),
[Pptx](../../com.groupdocs.editor.formats/presentationformats#Pptx).
プレゼンテーション形式の詳細は [こちら](../https://wiki.fileformat.com/presentation) で確認できます。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Ppt](#Ppt) | Microsoft PowerPoint 97-2003 プレゼンテーション (PPT)。 |
|
|  | [Ppt95](#Ppt95) | Microsoft PowerPoint 95 プレゼンテーション (PPT)。 |
|
|  | [Pptx](#Pptx) | Microsoft Office Open XML PresentationML マクロなしドキュメント (PPTX)。 |
|
|  | [Pptm](#Pptm) | Microsoft Office Open XML PresentationML マクロ有効ドキュメント (PPTM)。 |
|
|  | [Pps](#Pps) | Microsoft PowerPoint 97-2003 スライドショー (PPS)。 |
|
|  | [Ppsx](#Ppsx) | Microsoft Office Open XML PresentationML マクロなしスライドショー (PPSX)。 |
|
|  | [Ppsm](#Ppsm) | Microsoft Office Open XML PresentationML マクロ有効スライドショー (PPSM)。 |
|
|  | [Pot](#Pot) | Microsoft PowerPoint 97-2003 プレゼンテーションテンプレート (POT)。 |
|
|  | [Potx](#Potx) | Microsoft Office Open XML PresentationML マクロなしテンプレート (POTX)。 |
|
|  | [Potm](#Potm) | Microsoft Office Open XML PresentationML マクロ有効テンプレート (POTM)。 |
|
|  | [Odp](#Odp) | OpenDocument プレゼンテーション (ODP)。 |
|
|  | [Otp](#Otp) | OpenDocument プレゼンテーションテンプレート (OTP)。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべての [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) の列挙可能なコレクションを取得します。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 指定されたファイル拡張子を持つ、指定されたタイプの [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) インスタンスを取得します。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | ファイル拡張子を表す文字列を [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) オブジェクトに変換します。 |
|
### Ppt {#Ppt}
```
public static final PresentationFormats Ppt
```


Microsoft PowerPoint 97-2003 プレゼンテーション (PPT)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/ppt)
.


### Ppt95 {#Ppt95}
```
public static final PresentationFormats Ppt95
```


Microsoft PowerPoint 95 プレゼンテーション (PPT)。


### Pptx {#Pptx}
```
public static final PresentationFormats Pptx
```


Microsoft Office Open XML PresentationML マクロなしドキュメント (PPTX)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/pptx)
.


### Pptm {#Pptm}
```
public static final PresentationFormats Pptm
```


Microsoft Office Open XML PresentationML マクロ有効ドキュメント (PPTM)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/pptm)
.


### Pps {#Pps}
```
public static final PresentationFormats Pps
```


Microsoft PowerPoint 97-2003 スライドショー (PPS)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/pps)
.


### Ppsx {#Ppsx}
```
public static final PresentationFormats Ppsx
```


Microsoft Office Open XML PresentationML マクロなしスライドショー (PPSX)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/ppsx)
.


### Ppsm {#Ppsm}
```
public static final PresentationFormats Ppsm
```


Microsoft Office Open XML PresentationML マクロ有効スライドショー (PPSM)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/ppsm)
.


### Pot {#Pot}
```
public static final PresentationFormats Pot
```


Microsoft PowerPoint 97-2003 プレゼンテーションテンプレート (POT)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/pot)
.


### Potx {#Potx}
```
public static final PresentationFormats Potx
```


Microsoft Office Open XML PresentationML マクロなしテンプレート (POTX)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/potx)
.


### Potm {#Potm}
```
public static final PresentationFormats Potm
```


Microsoft Office Open XML PresentationML マクロ有効テンプレート (POTM)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/potm)
.


### Odp {#Odp}
```
public static final PresentationFormats Odp
```


OpenDocument プレゼンテーション (ODP)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/odp)
.


### Otp {#Otp}
```
public static final PresentationFormats Otp
```


OpenDocument プレゼンテーションテンプレート (OTP)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/presentation/otp)
.


### getAll() {#getAll--}
```
public static List<PresentationFormats> getAll()
```


すべての [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) の列挙可能なコレクションを取得します。
値: すべての [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) のインスタンスを含む IEnumerable{PresentationFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.PresentationFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static PresentationFormats fromExtension(String extension)
```


指定されたファイル拡張子を持つ、指定されたタイプの [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) インスタンスを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | ドキュメント形式のファイル拡張子です。 |
|

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) - An instance of the specified type [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static PresentationFormats fromString(String extension)
```


ファイル拡張子を表す文字列を [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | 変換するファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |
|

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) - A [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) object corresponding to the specified file extension.

