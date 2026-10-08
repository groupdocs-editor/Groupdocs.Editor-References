---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Presentation（PowerPoint 互換）ドキュメントの生成および保存のためのカスタムオプションを指定できます"
type: docs
weight: 1100
url: /ja/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

プレゼンテーション（PowerPoint 互換）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | このパラメータなしコンストラクタは、PPTX 出力形式で PresentationSaveOptions の新しいインスタンスを作成します（その後、[`OutputFormat`](./outputformat) プロパティで変更可能です） |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | 指定された必須の Presentation 出力形式で PresentationSaveOptions の新しいインスタンスを作成し、他のすべてのパラメータはデフォルトになります |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | ブールフラグで、編集されたスライドが [`SlideNumber`](./slidenumber) プロパティで指定された位置の元のプレゼンテーションの既存スライドを置き換えるか、既存スライドと前のスライドの間に挿入して内容を置き換えないかを指定します。デフォルトは `false` で、既存スライドが置き換えられます。[`SlideNumber`](./slidenumber) プロパティの値が `'0'` に設定されている場合、このプロパティは無視されます。 |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | ドキュメントの保存に使用される Presentation フォーマットを指定できます |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | 生成された Presentation ドキュメントのエンコードに使用されるパスワードを指定、変更、取得できます。デフォルトは NULL で、パスワードは設定されません。以前に設定されている場合は、NULL または空文字列に設定してパスワードを削除します。 |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | 新しい単一スライドのプレゼンテーションを作成する代わりに、編集されたスライドを既存のプレゼンテーションに挿入できます（デフォルトの動作）。スライド番号は、Editor クラスでロードされたプレゼンテーション内のスライドの 1 から始まる番号です。0（デフォルト値）の場合、新しいプレゼンテーションは単一の編集スライドで作成されます。0 より大きいまたは小さい場合で、Editor クラスで有効なプレゼンテーションがロードされていれば、入力の EditableDocument インスタンスに格納された編集スライドがそのプレゼンテーションに挿入されます。 |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | 編集されたスライドが既存のプレゼンテーションに挿入される場合に、保存時にプレゼンテーションから削除すべきスライドの 1 から始まる番号の配列を指定できます |

### 備考

このクラスのインスタンスは、編集されたプレゼンテーションを特定の Presentation フォーマットの最終ドキュメントに保存するためにメソッドに渡す必要があります。他のすべてのパラメータはオプションで省略可能で、デフォルトでは保存されるプレゼンテーションのフォーマットは PPTX ですが、コンストラクタまたはプロパティで変更できます。

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
