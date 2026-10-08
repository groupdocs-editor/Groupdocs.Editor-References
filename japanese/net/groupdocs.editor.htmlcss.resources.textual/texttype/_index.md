---
title: "TextType"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "サポート可能なテキストリソースタイプを 1 つ表します"
type: docs
weight: 640
url: /ja/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

サポート可能なテキストリソースタイプを 1 つ表します

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | テキストリソースの CSS タイプ |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | 未定義、未知、またはサポートされていないテキストリソースを示す特別な値 |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | テキストリソースの XML タイプ |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | 特定のテキストリソースのファイル拡張子（先頭のドット文字なし） |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | このテキストリソースタイプの正式名称を返します |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | 特定のテキストリソースタイプの MIME コード |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | 指定されたファイル名（拡張子付き）または純粋な拡張子から抽出されたファイル拡張子に相当する TextType 値を返します |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | このインスタンスが指定されたキャストされていないオブジェクト（おそらく別の "TextType" インスタンス）と等しいかどうかを判断します |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | このインスタンスが指定された "TextType" インスタンスと等しいかどうかを判断します |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | この特定の値型に対して一定の数値であるハッシュコードを返します |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | 2つの特定の "TextType" インスタンスが等しいかどうかを定義します |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | 2つの特定の "TextType" インスタンスが等しくないかどうかを定義します |

### 参照

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
