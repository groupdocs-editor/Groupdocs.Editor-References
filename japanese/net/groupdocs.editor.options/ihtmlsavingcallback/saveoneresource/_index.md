---
title: "SaveOneResource"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "インスタンス メソッドで、Savegroupdocs.editor/editabledocument/save メソッド呼び出し中にトリガーされ、エンドユーザーが提供された HTML リソースを取得して保存し、そのリソースへのリンクを呼び出し元に返すために実装しなければなりません。"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

インスタンス メソッドで、[`Save`](../../../groupdocs.editor/editabledocument/save) メソッド呼び出し中にトリガーされ、エンドユーザーが提供された HTML リソースを取得して保存し、そのリソースへのリンクを呼び出し元に返すために実装しなければなりません。

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| リソース | IHtmlResource | HTML リソース（画像やフォント、HTML マークアップに埋め込まれていない場合はスタイルシートも含む）で、GroupDocs.Editor がこのインターフェイスのユーザー定義実装に渡すものです。ユーザーは取得したリソースに対して保存、送信、変換など必要な手順を実行できます。GroupDocs.Editor はこのメソッドに `null` の HTML リソースを渡すことは決してありません。 |

### 戻り値

*resource* パラメータで取得したリソースへのリンク（参照）で、ユーザーはこれを GroupDocs.Editor に提供する必要があります。そうすると GroupDocs.Editor はこのリンクを HTML マークアップに挿入します。

### 備考

GroupDocs.Editor は、このメソッドのユーザー定義実装が実行中に例外をスローしないことを期待しています。ただし、例外が発生した場合、GroupDocs.Editor は [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) プロパティの値を HTML マークアップに書き込みます。

### 参照

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
