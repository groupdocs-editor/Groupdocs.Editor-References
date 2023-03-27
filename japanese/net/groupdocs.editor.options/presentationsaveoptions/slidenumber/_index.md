---
title: SlideNumber
second_title: GroupDocs.Editor for .NET API リファレンス
description: 新しい単一スライド プレゼンテーションを作成する代わりに編集済みのスライドを既存のプレゼンテーションに挿入できます 既定の動作 スライド番号はプレゼンテーション内のスライドの 1 から始まる番号でEditor クラスに読み込まれます 0 デフォルト値 の場合新しいプレゼンテーションは編集された単一のスライドで作成されます 0 より大きくても小さくても有効なプレゼンテーションが Editor クラスにロードされている場合入力 EditableDocument インスタンス内に保存された編集済みスライドがこのプレゼンテーションに挿入されます
type: docs
weight: 50
url: /ja/net/groupdocs.editor.options/presentationsaveoptions/slidenumber/
---
## PresentationSaveOptions.SlideNumber property

新しい単一スライド プレゼンテーションを作成する代わりに、編集済みのスライドを既存のプレゼンテーションに挿入できます (既定の動作)。 スライド番号は、プレゼンテーション内のスライドの 1 から始まる番号で、Editor クラスに読み込まれます。 0 (デフォルト値) の場合、新しいプレゼンテーションは編集された単一のスライドで作成されます。 0 より大きくても小さくても、有効なプレゼンテーションが Editor クラスにロードされている場合、入力 EditableDocument インスタンス内に保存された編集済みスライドがこのプレゼンテーションに挿入されます。

```csharp
public int SlideNumber { get; set; }
```

### 備考

スライド番号整数プロパティは、デフォルト状態 (予約値 '0') でない場合、スライド番号を表すため、0 からではなく 1 から始まり、その最大値はプレゼンテーション内の既存のすべてのスライドの量です。ただし、指定された値がすべてのスライドの量よりも大きい場合、GroupDocs.Editor はそれを調整して最後のスライドをマークします。負の値も許可され、最後からスライドをカウントします。たとえば、「-1」はプレゼンテーションの最後のスライドを意味し、「-2」は最後から 2 番目のスライドなどを意味します。正の値と同様に、負のスライド番号が特定のプレゼンテーションのスライドの合計数を超えると、次のように調整されます。最初のスライド. [`InsertAsNewSlide`](../insertasnewslide)ブール値のプロパティは、これと密接に結合されています.

### 例

与えられたプレゼンテーションには 5 つのスライドがあります: SlideNumber = 0; — 指定されたプレゼンテーションを無視して、新しいプレゼンテーションを作成し、編集したスライドをそこに挿入します。 SlideNumber = 1; — 最初のスライドを edited SlideNumber = 2 に置き換えます。 — 2 番目のスライドを edited SlideNumber = 5 に置き換えます。 — 最後の (5 番目の) スライドを edited SlideNumber = 6 に置き換えます。 — 6 は 5 より大きく、したがってadjusted SlideNumber = -1 であるため、最後 (5 番目) のスライドを編集済みのスライドに置き換えます。 — 「-1」は「最後の存在」を意味するため、最後 (5 番目) のスライドを編集済みのスライドに置き換えます SlideNumber = -2; — 4 番目のスライドを edited SlideNumber = -3 に置き換えます。 — 3 番目のスライドを edited SlideNumber = -4 に置き換えます。 — 2 番目のスライドを edited SlideNumber = -5 に置き換えます。 — 最初のスライドを edited SlideNumber = -6 に置き換えます。 — 最初のスライドを編集済みのスライドに置き換えます。"-6" は 5 より大きいため、adjusted です。

### 関連項目

* class [PresentationSaveOptions](../../presentationsaveoptions)
* 名前空間 [GroupDocs.Editor.Options](../../presentationsaveoptions)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->