---
title: FromMarkupAndResourceFolder
second_title: GroupDocs.Editor for .NET API リファレンス
description: 静的ファクトリ指定された HTML マークアップとリソースから EditableDocument のインスタンスを作成しフル パス で指定されたフォルダーに配置されます
type: docs
weight: 30
url: /ja/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

静的ファクトリ。指定された HTML マークアップとリソースから EditableDocument のインスタンスを作成し、フル パス で指定されたフォルダーに配置されます。

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newHtmlContent | String | 解析する必要がある生の HTML マークアップを含む文字列。 NULL、空、または無効にすることはできません。 |
| resourceFolderPath | String | リソースを含むフォルダーへの必須パス。このフォルダにあるすべてのスタイルシートが使用されます。 NULL または空の文字列にすることはできません。このフォルダーは存在する必要があります。 |

### 戻り値

EditableDocument の新しい非 null インスタンス

### 備考

この静的ファクトリは、HTML ドキュメントのコンテンツが文字列として表示される場合に役立ちますが、すべてのリソースが特定のフォルダーに配置されており、多くの場合、HTML マークアップ内のこれらのリソースへのリンクが無効であり、存在しません。このメソッドを呼び出すと、指定されたフォルダーがスキャンされ、見つかったすべてのスタイルシートがドキュメントに自動的に適用されます。このメソッドは、さまざまな HTML エディターからコンテンツを取得する場合に非常に役立ちます。通常、ドキュメントのメタデータなどが切り取られます。

### 関連項目

* class [EditableDocument](../../editabledocument)
* 名前空間 [GroupDocs.Editor](../../editabledocument)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
