---
title: "ImageType"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ラスタ形式とベクター形式の両方をサポートする、1つのサポート可能な画像タイプフォーマットを表します"
type: docs
weight: 480
url: /ja/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

サポート可能な画像タイプ（フォーマット）を表し、ラスタとベクタの両方のフォーマットをサポートします。

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | BMP 画像タイプ |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | EMF（拡張メタファイル）ベクター画像タイプ |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | GIF 画像タイプ |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | ICON 画像タイプ |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | JPEG 画像タイプ |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | PNG 画像タイプ |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | SVG ベクター画像タイプ |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | TIFF（タグ付け画像ファイル形式）ラスタ画像タイプ |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | 未定義画像タイプ - 通常は発生しない特別な値 |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | WMF（Windows メタファイル）ベクター画像タイプ |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | 特定の画像タイプのファイル拡張子（先頭のドット文字なし）を小文字で表します。未定義タイプの場合は文字列 'unsefined' を返します。 |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | この画像フォーマットの正式名称を返します。決して NULL を返しません。インスタンスが破損していない限り、例外をスローすることもありません。 |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | この特定のフォーマットがベクター（true）かラスタ（false）かを示します |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | 特定の画像タイプの MIME コードを文字列として返します。未定義タイプの場合は文字列 'unsefined' を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | 指定されたファイル名から抽出されたファイル拡張子に相当する ImageType 値を返します |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | 指定された MIME コードに相当する ImageType 値を返します |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | このインスタンスが指定された "ImageType" インスタンスと等しいかどうかを判定します |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します。おそらく別の "ImageType" インスタンスです。 |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | この特定のインスタンスに対する不変の数値であるハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | FormalName プロパティを返します。 |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | 2つの特定の ImageType インスタンスが等しいかどうかを定義します。 |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | 2つの特定の ImageType インスタンスが等しくないかどうかを定義します。 |

### 参照

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
