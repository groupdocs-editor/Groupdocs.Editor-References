---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "このパラメータなしコンストラクタは、セミコロンをデフォルト区切り文字とした DelimitedTextSaveOptions の新しいインスタンスを作成します。区切り文字はその後、Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator プロパティを介して変更できます。"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

このパラメータなしコンストラクタは、セミコロン (;) をデフォルト区切り文字とした DelimitedTextSaveOptions の新しいインスタンスを作成します。区切り文字はその後、[`Separator`](../separator) プロパティを介して変更できます。

```csharp
public DelimitedTextSaveOptions()
```

### 参照

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

必須の区切り文字（デリミタ）を指定して、区切りテキスト用オプションクラスのインスタンスを作成します

```csharp
public DelimitedTextSaveOptions(string separator)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| separator | 文字列 | NULL または空にできない文字列区切り文字（デリミタ） |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された区切り文字が null または空文字列の場合にスローされます。 |

### 参照

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
