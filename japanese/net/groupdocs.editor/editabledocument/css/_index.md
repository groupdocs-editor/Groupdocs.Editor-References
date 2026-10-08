---
title: "Css"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "このHTMLドキュメントで使用されている、外部および埋め込みの（インラインではない）CSSスタイルシートリソースを取得できます"
type: docs
weight: 60
url: /ja/net/groupdocs.editor/editabledocument/css/
---
## EditableDocument.Css property

この HTML ドキュメントで使用されているスタイルシート (CSS) リソース（外部および埋め込み、インラインは除く）を取得できるようにします

```csharp
public List<CssText> Css { get; }
```

### 備考

このメソッドは使用されたすべてのスタイルシートリソースの浅いコピーを返します：`List` は呼び出しごとに新しいインスタンスですが、リソースインスタンスは同じです。

### 参照

* class [CssText](../../../groupdocs.editor.htmlcss.resources.textual/csstext)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
