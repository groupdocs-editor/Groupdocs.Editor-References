---
title: "Save"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "この HTML ドキュメントを、HTML マークアップが保存される指定パスのファイルと、リソースが格納される付随フォルダーに保存します。"
type: docs
weight: 160
url: /ja/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

指定されたパスに HTML マークアップを保存し、リソース用の付随フォルダーに保存することで、この HTML ドキュメントをファイルに保存します

```csharp
public void Save(string htmlFilePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlFilePath | 文字列 | HTML マークアップが保存されるファイルへの完全パスです。ファイルが存在する場合は作成または上書きされます。付随するリソースフォルダーは、HTML ファイルが存在する同じフォルダーに作成されます。 |

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

指定されたパスに HTML マークアップを保存し、リソース用の付随フォルダー（指定されたパスに位置する）に保存することで、この HTML ドキュメントをファイルに保存します

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlFilePath | 文字列 | HTML マークアップが保存されるファイルへの完全パスです。NULL または空であってはなりません。ファイルが存在する場合は作成または上書きされます。 |
| resourcesFolderPath | 文字列 | すべての関連リソースが格納される付随フォルダーへの完全パスです。NULL または空の場合、*.html ファイルと同じディレクトリにフォルダーが自動的に作成されます。指定されていて存在しない場合は作成されます。 |

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

この [`EditableDocument`](../../editabledocument) の内容を HTML ドキュメントとして指定されたテキストライターに保存し、2 番目のオプションパラメーターで保存手順をカスタマイズし、リソース保存コールバックを指定できます。

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlMarkup | TextWriter | HTML マークアップが書き込まれるテキストライターの実装です。null にはできません。 |
| saveOptions | HtmlSaveOptions | HTML 保存オプションは、保存手順を制御します：HTML マークアップの保存方法（タグ名、引用符の種類）や、CSS や画像、フォントなどのリソースの保存場所と方法。ユーザーは、[`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) プロパティでインターフェイスの継承クラスを指定し、リソースの保存方法と HTML マークアップからの参照方法を制御する必要があります。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | 指定された引数のいずれか、または *saveOptions* の `SavingCallback` プロパティが `null` です。 |

### 参照

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
