---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "フォーマットファミリのインスタンスに共通機能を提供する、フォーマットファミリの基底クラスを表します。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

フォーマットファミリーの基底クラスを表し、フォーマットファミリーインスタンスに共通の機能を提供します。

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | このインスタンスが指定された [`FormatFamilyBase`](../formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | 指定された名前を持つ、指定された型 *T* のインスタンスを取得します。 |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | 指定された識別子を持つ、指定された型 *T* のインスタンスを取得します。 |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | [`FormatFamilyBase`](../formatfamilybase) から派生する、指定された型 *T* のすべてのインスタンスを取得します。 |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | 2 つの [`FormatFamilyBase`](../formatfamilybase) インスタンスが等しいかどうかを判断します。 (2 operators) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | フォーマットファミリ名を表す文字列を [`FormatFamilyBase`](../formatfamilybase) オブジェクトに変換します。 (2 operators) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | [`FormatFamilyBase`](../formatfamilybase) インスタンスを暗黙的に整数に変換します。 (2 operators) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | 2 つの [`FormatFamilyBase`](../formatfamilybase) インスタンスが等しくないかどうかを判断します。 (2 operators) |

### 備考

このクラスは抽象クラスであり、実際のフォーマットファミリの詳細を指定する派生クラスによって継承される必要があります。

### 参照

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
