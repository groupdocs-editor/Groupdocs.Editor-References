---
title: "Edit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定されたフォーマット固有オプションを使用して、以前に読み込まれたドキュメントを編集用に開き、EditableDocumentgroupdocs.editor/editabledocument クラスのインスタンスを生成して返します。このインスタンスは、HTML マークアップと関連リソースを生成するメソッドを含んでいます。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

指定されたフォーマット固有オプションを使用して、以前に読み込まれたドキュメントを編集用に開き、'[`EditableDocument`](../../editabledocument)' クラスのインスタンスを生成して返します。このインスタンスは、HTML マークアップと関連リソースを生成するメソッドを含んでいます。

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| editOptions | IEditOptions | フォーマット固有のドキュメントオプションで、変換プロセスを調整できます。NULL の場合、GroupDocs.Editor は以前に読み込まれたドキュメントのフォーマットを検出し、そのフォーマットのデフォルトオプションを適用します。以前に適用されたロードオプションと競合しないようにしてください。 |

### 戻り値

'[`EditableDocument`](../../editabledocument)' クラスのインスタンスで、すべてのリソースを含む入力ドキュメント全体を中間フォーマットでカプセル化します。このメソッドは、正常に完了した場合、決して NULL を返しません。

### 備考

入力の元ドキュメントがコンストラクタを通じて 'Editor' インスタンスにロードされると、このメソッドはドキュメントを中間フォーマットに変換して編集用に開くことを可能にします。その中間フォーマットは 'EditableDocument' クラスのインスタンスにカプセル化されます。'[`EditableDocument`](../../editabledocument)' はこのメソッドから返され、HTML マークアップと対応するリソース（画像、フォント、スタイルシートなど）を生成するために必要なすべてのメソッドとプロパティを提供し、任意の WYSIWYG HTML エディタに渡すためのすべての構成で利用できます。このオーバーロードは、ファミリーフォーマット固有の編集オプションを取得します。**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### 参照

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

デフォルトオプションを使用して、以前に読み込まれたドキュメントを編集用に開き、'[`EditableDocument`](../../editabledocument)' クラスのインスタンスを生成して返します。このインスタンスは、HTML マークアップと関連リソースを生成するメソッドを含んでいます。

```csharp
public EditableDocument Edit()
```

### 戻り値

'[`EditableDocument`](../../editabledocument)' クラスのインスタンスで、すべてのリソースを含む入力ドキュメント全体を中間フォーマットでカプセル化します。このメソッドは、正常に完了した場合、決して NULL を返しません。

### 備考

入力の元ドキュメントがコンストラクタを通じて 'Editor' インスタンスにロードされると、このメソッドはドキュメントを中間フォーマットに変換して編集用に開くことを可能にします。その中間フォーマットは '[`EditableDocument`](../../editabledocument)' クラスのインスタンスにカプセル化されます。返された '[`EditableDocument`](../../editabledocument)' は、HTML マークアップと対応するリソース（画像、フォント、スタイルシートなど）を生成するために必要なすべてのメソッドとプロパティを提供し、任意の WYSIWYG HTML エディタに渡すためのすべての構成で利用できます。このオーバーロードは、入力ドキュメントが属するフォーマットのデフォルト編集オプションを適用します。**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### 参照

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
