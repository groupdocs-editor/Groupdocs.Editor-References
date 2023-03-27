---
title: Edit
second_title: GroupDocs.Editor for .NET API リファレンス
description: EditableDocumentgroupdocs.editor/editabledocumentこのクラスにはHTML マークアップと関連するリソースを生成するためのメソッドが含まれています.
type: docs
weight: 50
url: /ja/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

'[`EditableDocument`](../../editabledocument)このクラスには、HTML マークアップと関連するリソースを生成するためのメソッドが含まれています.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| editOptions | IEditOptions | 変換プロセスを調整できるフォーマット固有のドキュメント オプション。 NULL の可能性があります — その場合、GroupDocs.Editor は以前に読み込まれたドキュメントの形式を検出し、オプション (この形式のデフォルト) を適用します。以前に適用されたロード オプションと競合してはなりません。 |

### 戻り値

' のインスタンス[`EditableDocument`](../../editabledocument)このクラスは、入力ドキュメント全体をそのすべてのリソースとともに中間形式でカプセル化します。このメソッドは、正常に終了した場合、NULL を返しません。

### 備考

入力元のドキュメントがコンストラクターを介して「Editor」インスタンスにロードされると、このメソッドは、「EditableDocument」クラスのインスタンス内にカプセル化された中間形式に変換することにより、編集用にドキュメントを開くことができます。 '[`EditableDocument`](../../editabledocument)このメソッドから返される には、HTML マークアップと対応するリソース (画像、フォント、スタイルシートなど) を生成するために必要なすべてのメソッドとプロパティが含まれており、後でそれらを任意の WYSIWYG HTML エディターに渡すために必要なすべての構成が含まれています。このオーバーロードは、ファミリ形式に固有の編集オプションを取得します. **もっと詳しく知る**

* GroupDocs.Editor: を使用したドキュメントの編集の詳細[GroupDocs.Editor を使用してドキュメントを編集する方法](https://docs.groupdocs.com/display/editornet/Edit+document)

### 関連項目

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* 名前空間 [GroupDocs.Editor](../../editor)
* 組み立て [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

'[`EditableDocument`](../../editabledocument)このクラスには、HTML マークアップと関連するリソースを生成するためのメソッドが含まれています.

```csharp
public EditableDocument Edit()
```

### 戻り値

' のインスタンス[`EditableDocument`](../../editabledocument)このクラスは、入力ドキュメント全体をそのすべてのリソースとともに中間形式でカプセル化します。このメソッドは、正常に終了した場合、NULL を返しません。

### 備考

入力元のドキュメントがコンストラクターを介して 'Editor' インスタンスにロードされると、このメソッドは、'[`EditableDocument`](../../editabledocument)クラス。 '[`EditableDocument`](../../editabledocument)このメソッドから返される には、HTML マークアップと対応するリソース (画像、フォント、スタイルシートなど) を生成するために必要なすべてのメソッドとプロパティが含まれており、後でそれらを任意の WYSIWYG HTML エディターに渡すために必要なすべての構成が含まれています。このオーバーロードは、入力ドキュメントが属するフォーマットのデフォルトである編集オプションを適用します. **もっと詳しく知る**

* GroupDocs.Editor: を使用したドキュメントの編集の詳細[GroupDocs.Editor を使用してドキュメントを編集する方法](https://docs.groupdocs.com/display/editornet/Edit+document)

### 関連項目

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* 名前空間 [GroupDocs.Editor](../../editor)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->