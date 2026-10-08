---
title: "IHtmlResource"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "不明な HTML リソース（ラスタ画像またはベクタ画像、スタイルシート、フォント、テキスト、CSS、XML、オーディオ等）のインスタンスを表します"
type: docs
weight: 430
url: /ja/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

未知の HTML リソース（ラスタ画像またはベクター画像、スタイルシート、フォント、テキストリソース（CSS、XML）、オーディオ等）の 1 つのインスタンスを表します

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | HTML リソースの内容をバイトストリーム形式で表します |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | 適切なファイル拡張子を付けた、指定されたリソースの正しいファイル名 |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | HTML リソースの名前 |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | バイナリリソースの場合は base64 エンコードされたテキスト文字列、テキストリソースの場合は単純なテキストとして表された HTML リソースの内容 |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | HTML リソースのタイプ |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | 現在のリソースを指定されたファイルに保存します |

### 参照

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
