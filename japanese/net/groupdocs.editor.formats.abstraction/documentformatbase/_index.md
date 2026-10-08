---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ドキュメント形式のベースクラスを表し、形式インスタンスに共通の機能を提供します。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

ドキュメントフォーマットの基底クラスを表し、フォーマットインスタンスに共通の機能を提供します。

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | このインスタンスが指定された [`DocumentFormatBase`](../documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | 指定された MIME タイプを持つ、指定された型 *T* のインスタンスを取得します。 |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | [`DocumentFormatBase`](../documentformatbase) インスタンスを暗黙的に文字列に変換します。 |

### 参照

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
