---
title: "FromMarkupAndResourceFolder"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された HTML マークアップと、フルパスで指定されたフォルダーにあるリソースから EditableDocument のインスタンスを作成する静的ファクトリです"
type: docs
weight: 30
url: /ja/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

静的ファクトリで、指定された HTML マークアップと、フルパスで指定されたフォルダー内にあるリソースから EditableDocument のインスタンスを作成します

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newHtmlContent | 文字列 | 解析すべき生の HTML マークアップを含む文字列。NULL、空、または無効であってはなりません。 |
| resourceFolderPath | 文字列 | リソースフォルダーへの必須パス。このフォルダーにあるすべてのスタイルシートが使用されます。NULL または空文字列であってはならず、フォルダーは存在する必要があります。 |

### 戻り値

新しい null でない EditableDocument インスタンス

### 備考

この静的ファクトリは、HTML ドキュメントの内容が文字列として提供されているが、すべてのリソースがあるフォルダーに格納されていて、HTML マークアップ内のリソースへのリンクが無効または欠落している場合に便利です。このメソッドを呼び出すと、指定されたフォルダーをスキャンし、見つかったすべてのスタイルシートを自動的にドキュメントに適用します。このメソッドは、通常ドキュメントのメタデータなどが切り取られるさまざまな HTML エディタからコンテンツを取得する際に非常に有用です。

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
