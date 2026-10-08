---
title: "FromFile"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "HTML ファイル（.html ファイル自体へのパス）とリンクされたリソースが格納されたフォルダーを指定して、EditableDocument のインスタンスを作成する静的ファクトリです。"
type: docs
weight: 10
url: /ja/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

静的ファクトリで、*.html ファイルへのパスとリンクされたリソースが格納されたフォルダーを指定して、HTML ファイルから EditableDocument のインスタンスを作成します

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlFilePath | 文字列 | HTML ファイルへの完全パスを含む文字列です。null であってはならず、有効なファイルパスであり、ファイル自体が存在する必要があります。 |
| resourceFolderPath | 文字列 | HTML リソースが格納されたフォルダーへのオプションのパスです。NULL、無効、またはフォルダーが存在しない場合、エディターは HTML マークアップを解析して自動的にこのフォルダーを探します。 |

### 戻り値

新しい null でない EditableDocument インスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | HTML ファイルのパス、またはリソースフォルダーのパスが無効です。 |
| FileNotFoundException | 指定された HTML ファイルが見つかりません。 |

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
