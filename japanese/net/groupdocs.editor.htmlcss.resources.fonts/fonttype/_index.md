---
title: "FontType"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "サポート可能なフォントタイプを表します。"
type: docs
weight: 360
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

サポート可能なフォントタイプを表します。

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | EOT（Embedded OpenType）フォントタイプを表します |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | OTF（OpenType Font）フォントタイプを表します |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | TrueType Collection（TTC）フォントを表します |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | TTF（TrueType Font）フォントタイプを表します |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | 未定義、未知、またはサポートされていないフォントリソースを示す特別な値 |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | WOFF（Web Open Font Format）フォントタイプを表します |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | WOFF2（Web Open Font Format バージョン 2）フォントタイプを表します |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | このフォントタイプの CSS 互換名を返します（@font-face ルールで使用されます） |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | このフォントタイプのファイル名拡張子（ドット文字なし） |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | @font-face 用のフォント形式 |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | このフォントタイプの正式名称を返します |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | 特定のフォントタイプの MIME コード |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | 指定されたセットから最初の"Undefined"以外のフォントタイプを返します。すべてが"Undefined"の場合は"Undefined"フォントタイプを返します |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | 指定されたフォントタイプの CSS 互換名に相当する FontType 値を返します |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | 指定されたファイル名から抽出された拡張子に相当する FontType 値を返します |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | 指定された MIME コードに相当する FontType 値を返します |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | このインスタンスが指定された"FontType"インスタンスと等しいかどうかを判定します |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判断します。これはおそらく別の "FontType" インスタンスです。 |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | この特定の値型に対して一定の数値であるハッシュコードを返します |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | 二つの "FontType" 値が等しいかどうかをチェックします |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | 二つの "FontType" 値が等しくないかどうかをチェックします |

### 参照

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
