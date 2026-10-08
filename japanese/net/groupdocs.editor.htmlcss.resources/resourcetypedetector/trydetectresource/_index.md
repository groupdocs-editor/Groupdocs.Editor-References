---
title: "TryDetectResource"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "入力ストリームを解析し、指定された仮定タイプ（null でない場合）を考慮してサポート可能な HTML リソースのいずれかを作成しようとします"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

入力ストリームを解析し、サポート可能な HTML リソースのいずれかを作成します。指定された仮定タイプが null でない場合はそれを考慮します。

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputResourceStream | Stream | HTML リソースを含むと想定される入力ストリーム。無効な場合は例外がスローされます |
| 名前 | 文字列 | 成功時に作成および返却されるリソースに使用されるリソース名。NULL、空文字、または空白のみであってはなりません |
| assumptiveFormat | IResourceType | 入力 HTML リソースの想定フォーマット。最高のパフォーマンスを得るために有用です。完全に不明な場合は NULL を使用してください。誤っている可能性があり、その場合はパフォーマンスが低下します |

### 戻り値

成功時にサポート可能な HTML リソースのいずれかを表す、'IHtmlResource' インターフェイスを実装したインスタンス。失敗時は NULL

### 参照

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
