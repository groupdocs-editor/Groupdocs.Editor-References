---
title: "SlideNumber"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "編集されたスライドを新しい単一スライドプレゼンテーションを作成する代わりに、既存のプレゼンテーションに挿入できるようにします（デフォルトの動作）。スライド番号は、Editor クラスで読み込まれたプレゼンテーション内のスライドの 1 ベース番号です。0 の場合はデフォルト値となり、新しいプレゼンテーションが単一の編集スライドで作成されます。0 より大きいまたは小さい場合で、Editor クラスに有効なプレゼンテーションが読み込まれていると、入力 EditableDocument インスタンス内に保存された編集スライドがそのプレゼンテーションに挿入されます。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.options/presentationsaveoptions/slidenumber/
---
## PresentationSaveOptions.SlideNumber property

新しい単一スライドのプレゼンテーションを作成する代わりに、編集されたスライドを既存のプレゼンテーションに挿入できます（デフォルトの動作）。スライド番号は、Editor クラスでロードされたプレゼンテーション内のスライドの 1 から始まる番号です。0（デフォルト値）の場合、新しいプレゼンテーションは単一の編集スライドで作成されます。0 より大きいまたは小さい場合で、Editor クラスで有効なプレゼンテーションがロードされていれば、入力の EditableDocument インスタンスに格納された編集スライドがそのプレゼンテーションに挿入されます。

```csharp
public int SlideNumber { get; set; }
```

### 備考

SlideNumber 整数プロパティで、デフォルト状態（予約値 '0'）でない場合、スライド番号を表します。したがって 1 から始まり、0 からは始まりません。また、その最大値はプレゼンテーション内の既存スライドすべての数です。ただし、指定された値がスライド総数を超える場合、GroupDocs.Editor は最後のスライドを指すように調整します。負の値も許可され、末尾からスライドを数えます。たとえば \"-1\" はプレゼンテーションの最後のスライド、\"-2\" は最後から2番目、というようにです。正の値と同様に、負のスライド番号がプレゼンテーションの総スライド数を超える場合、最初のスライドに調整されます。[`InsertAsNewSlide`](../insertasnewslide) ブールプロパティはこのプロパティと密接に連動しています。

### 例

プレゼンテーションに 5 枚のスライドがあるとします: SlideNumber = 0; — 指定されたプレゼンテーションを無視し、新しいプレゼンテーションを作成して編集スライドを配置します。 SlideNumber = 1; — 最初のスライドを編集スライドで置き換えます。 SlideNumber = 2; — 2 番目のスライドを編集スライドで置き換えます。 SlideNumber = 5; — 最後（5 番目）のスライドを編集スライドで置き換えます。 SlideNumber = 6; — 6 は 5 を超えるため、最後のスライドに調整され、最後（5 番目）のスライドを編集スライドで置き換えます。 SlideNumber = -1; — \"-1\" は「最後の既存スライド」を意味し、最後（5 番目）のスライドを編集スライドで置き換えます。 SlideNumber = -2; — 4 番目のスライドを編集スライドで置き換えます。 SlideNumber = -3; — 3 番目のスライドを編集スライドで置き換えます。 SlideNumber = -4; — 2 番目のスライドを編集スライドで置き換えます。 SlideNumber = -5; — 最初のスライドを編集スライドで置き換えます。 SlideNumber = -6; — \"-6\" は 5 を超えるため、最初のスライドに調整され、最初のスライドを編集スライドで置き換えます。

### 参照

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
