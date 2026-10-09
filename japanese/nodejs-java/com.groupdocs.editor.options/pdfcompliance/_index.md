---
title: "PdfCompliance"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PDF 標準準拠レベルを指定します。"
type: docs
weight: 28
url: /ja/nodejs-java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

PDF 標準準拠レベルを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Pdf17](#Pdf17) | PDF 1.7（ISO 32000-1）標準 |
|
|  | [Pdf20](#Pdf20) | PDF 2.0（ISO 32000-2）標準 |
|
|  | [PdfA1a](#PdfA1a) | PDF/A-1a 標準。 |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b（ISO 19005-1）。 |
|
|  | [PdfA2a](#PdfA2a) | PDF/A-2a（ISO 19005-2）標準。 |
|
|  | [PdfA2u](#PdfA2u) | PDF/A-2u（ISO 19005-2）標準。 |
|
|  | [PdfUa1](#PdfUa1) | PDF/UA-1（ISO 14289-1）標準。 |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7（ISO 32000-1）標準


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0（ISO 32000-2）標準


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a 標準。このレベルは PDF/A-1b のすべての要件を含み、さらに文書構造の含有を要求します
（「タグ付け」されていることとしても知られ）、文書内容が検索可能で再利用できるようにすることを目的としています。

<br />

*** ** * ** ***

文書構造をエクスポートするとメモリ使用量が大幅に増加することに注意してください。特に大きな文書では顕著です。

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b（ISO 19005-1）。PDF/A-1b の目的は、文書の視覚的外観を信頼性高く再現できるようにすることです。


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a（ISO 19005-2）標準。このレベルは PDF/A-2u のすべての要件を含み、さらに文書構造の含有（「タグ付け」されていることとしても知られる）を要求し、文書内容が検索可能で再利用できるようにすることを目的としています。

<br />

*** ** * ** ***

文書構造をエクスポートするとメモリ使用量が大幅に増加することに注意してください。特に大きな文書では顕著です。

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u（ISO 19005-2）標準。PDF/A-2u の目的は、作成・保存・レンダリングに使用されるツールやシステムに依存せず、時間が経っても文書の静的な視覚外観を保持することです。さらに、文書に含まれるテキストは Unicode コードポイントの系列として信頼性高く抽出できます。


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1（ISO 14289-1）標準。PDF/UA の主な目的は、PDF 形式で電子文書を表現し、ファイルがアクセシブルになるように定義することです。


