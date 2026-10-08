---
title: "IHtmlSavingCallback"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "HTML形式で保存する際に使用されるインターフェイスで、提供されたリソースを保存し、そのリンクを返すためにエンドユーザーが実装しなければならないもの"
type: docs
weight: 920
url: /ja/net/groupdocs.editor.options/ihtmlsavingcallback/
---
## IHtmlSavingCallback interface

HTML 形式で保存する際に使用され、提供されたリソースを保存し、そのリンクを返すためにエンドユーザーが実装しなければならないインターフェイスです。

```csharp
public interface IHtmlSavingCallback
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SaveOneResource](../../groupdocs.editor.options/ihtmlsavingcallback/saveoneresource)(IHtmlResource) | インスタンス メソッドで、[`Save`](../../groupdocs.editor/editabledocument/save) メソッド呼び出し中にトリガーされ、エンドユーザーが提供された HTML リソースを取得して保存し、そのリソースへのリンクを呼び出し元に返すために実装しなければなりません。 |

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
