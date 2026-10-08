---
title: "FromMarkup"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された HTML マークアップから EditableDocumentgroupdocs.editor/editabledocument のインスタンスを作成する静的ファクトリです。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

指定された HTML マークアップから [`EditableDocument`](../../editabledocument) のインスタンスを作成する静的ファクトリです。

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newHtmlContent | 文字列 | 解析すべき生の HTML マークアップを含む文字列。NULL、空、または無効であってはなりません。 |

### 戻り値

新しい null でない EditableDocument インスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 入力された生の HTML マークアップ文字列は null または空にできません。 |

### 備考

この静的メソッドは、単一文字列の HTML マークアップから [`EditableDocument`](../../editabledocument) インスタンスを作成する際に便利です。すべてのリソースが base64 エンコードで埋め込まれます。

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

静的ファクトリで、指定された HTML マークアップと対応するリンクリソースのセットから EditableDocument のインスタンスを作成します

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newHtmlContent | 文字列 | 解析すべき生の HTML マークアップを含む文字列。NULL、空、または無効であってはなりません。 |
| resources | IEnumerable`1 | *newHtmlContent* パラメータで指定された HTML ドキュメントで使用されるすべてのリソース（画像、スタイルシート、フォント）のコレクションです。存在しない場合があります（NULL または空のコレクション）。 |

### 戻り値

新しい null でない EditableDocument インスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 入力された生の HTML マークアップ文字列は null または空にできません。 |

### 参照

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
