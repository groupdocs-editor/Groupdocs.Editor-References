---
title: "LocaleFarEast"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "WordProcessing ドキュメントの作成時に適用される東アジアテキスト用のロケール言語を上書き設定できるようにします。指定しない場合、既定値は MS Word などのプログラムが独自の設定やその他の要因に基づいて東アジアロケールを検出または選択します。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.options/wordprocessingsaveoptions/localefareast/
---
## WordProcessingSaveOptions.LocaleFarEast property

東アジアテキスト用の WordProcessing ドキュメントのロケール (言語) を上書きできるようにします。作成時に適用されます。指定されない場合 (デフォルト値)、MS Word (または他のプログラム) は独自の設定やその他の要因に基づいてドキュメントの東アジアロケールを検出 (または選択) します。

```csharp
public CultureInfo LocaleFarEast { get; set; }
```

### 備考

このオプションは、指定されたロケールをドキュメント全体の東アジアテキストに強制的に適用します。異なる言語で記述されたテキストが混在する場合は使用しないでください。

### 参照

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
