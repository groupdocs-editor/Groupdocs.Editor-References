---
title: PresentationFormats
second_title: GroupDocs.Editor for .NET API リファレンス
description: すべてのプレゼンテーション形式をカプセル化します次の形式が含まれます Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. プレゼンテーション形式の詳細ここhttps//wiki.fileformat.com/presentation.
type: docs
weight: 110
url: /ja/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

すべてのプレゼンテーション形式をカプセル化します。次の形式が含まれます: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). プレゼンテーション形式の詳細[ここ](https://wiki.fileformat.com/presentation).

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | このプレゼンテーション形式の拡張子 (先頭のドット文字なし) を小文字で返します |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | このフォーマットの MIME コードを返します |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | このプレゼンテーション形式の正式な完全な名前を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | のインスタンスを返します[`PresentationFormats`](../presentationformats)指定されたファイル拡張子に関連付けられた構造体、または拡張子を適切に解析できない場合は例外をスローします |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | このインスタンスが他の指定された IDocumentFormat と等しいかどうかを判断します instance |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | このインスタンスが、おそらくボックス化された PresentationFormats の他の指定されたオブジェクトと等しいかどうかを判断します |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | このインスタンスが他の指定された PresentationFormats と等しいかどうかを判断します instance |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | このインスタンスに対して不変のハッシュコードを返します |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | equality で指定された 2 つの PresentationFormats インスタンスをチェックします。 |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | inequality で指定された 2 つの PresentationFormats インスタンスをチェックします |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument プレゼンテーション (ODP) ファイルは、OASISOpen 標準で OpenOffice.org が使用するプレゼンテーション ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/odp) |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument プレゼンテーション テンプレート (OTP) ファイルは、OASIS OpenDocument 標準形式のアプリケーションによって作成されたプレゼンテーション テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/otp) |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 プレゼンテーション テンプレート (POT) ファイルは、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pot) |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) は、マクロをサポートするファイルです。 POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成するために使用できる既定の設定が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potm) |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX) ファイルは、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potx) |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 スライドショー (PPS) ファイルは、スライド ショーの目的で Microsoft PowerPoint を使用して作成されます。 PPS ファイルの読み取りと作成は、Microsoft PowerPoint 97-2003 でサポートされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pps) |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) ファイルは、Microsoft PowerPoint 2007 以降で作成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX) ファイルは、スライド ショー用に Microsoft PowerPoint 2007 以降を使用して作成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint プレゼンテーション (.ppt) は、スライドショーとして表示するスライドのコレクションで構成される PowerPoint ファイルを表します。 Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 プレゼンテーション (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft PowerPoint 2007 以降のバージョンで作成された Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM) ファイル。これらは PPTX ファイルに似ていますが、マクロを含めることはできますが、ラテラルはマクロを実行できないという違いがあります。 このファイル形式について詳しく知る[ここ](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML プレゼンテーション (.pptx) は、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。バイナリであった以前のバージョンのプレゼンテーション ファイル形式 PPT とは異なり、PPTX 形式は Microsoft PowerPoint オープン XML プレゼンテーション ファイル形式に基づいています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptx) |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | 既存のすべてのプレゼンテーション形式で列挙可能な可能性を提供する内部クラスを返します |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | IEnumerable ジェネリック インターフェイスを実装し、PresentationFormats type の「foreach」の可能性を有効にします |

### 関連項目

* interface [IDocumentFormat](../idocumentformat)
* 名前空間 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
