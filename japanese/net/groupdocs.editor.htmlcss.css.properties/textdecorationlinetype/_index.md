---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "テキスト装飾ラインの種類（underline、underscore、overline、linethrough（取り消し線））を表します"
type: docs
weight: 290
url: /ja/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

テキスト装飾線のタイプを表します：下線（アンダースコア）、上線、取り消し線（ストライクスルー）

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | このインスタンスに初期値（None）があるかどうかを示します |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | 取り消し線（line-through）が有効かどうかを示します |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | 上線（overline）が有効かどうかを示します |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | 下線（underline、underscore）が有効かどうかを示します |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | このインスタンス内のすべてのフラグの値をテキストとして返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | 指定されたパラメーターで定義されたフラグを持つ [`TextDecorationLineType`](../textdecorationlinetype) インスタンスを作成し、返します |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | この [`TextDecorationLineType`](../textdecorationlinetype) インスタンスが指定されたキャストされていない値と等しいかどうかを示します |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | この [`TextDecorationLineType`](../textdecorationlinetype) インスタンスが指定された値と等しいかどうかを示します |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | このインスタンスのハッシュコードを返します |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | このインスタンス内のすべてのフラグの値をテキストとして返します |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | 指定された文字列を解析し、有効な [`TextDecorationLineType`](../textdecorationlinetype) インスタンスを返そうとします |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | 指定された2つのラインタイプを結合（マージ）し、フラグが統合（union）された新しい結果のラインタイプを生成します |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | 最初と2番目のラインタイプの交差を返します。両方のオペランドで同時に有効なフラグのみが有効になります。すべての演算子の中で最も優先度が高く（unionやdifferenceよりも高い） |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | 2つの \"TextDecorationLineType\" 値が等しいかどうかをチェックします |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | 特定の Byte（8ビットオクテット）を対応する [`TextDecorationLineType`](../textdecorationlinetype) にキャストし、キャストが無効な場合は例外をスローします（2つの演算子） |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | 2つの \"TextDecorationLineType\" 値が等しくないかどうかをチェックします |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | 2番目に指定されたラインタイプを最初に指定されたラインタイプから減算し、2番目のオペランドに存在しない最初のオペランドのフラグのみが残る新しい結果のラインタイプを生成します（difference） |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | 各テキスト行の中央にラインが引かれています。 |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | テキスト装飾を生成しません。初期値です。 |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | 各テキスト行の上に行があります。 |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | 各テキスト行は下線が引かれています。 |

### 備考

不変構造体です。https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line と同様です。

### 参照

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
