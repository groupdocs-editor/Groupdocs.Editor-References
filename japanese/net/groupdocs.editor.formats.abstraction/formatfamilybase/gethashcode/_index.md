---
title: "GetHashCode"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "現在のオブジェクトのハッシュコードを返します。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

現在のオブジェクトのハッシュコードを返します。

```csharp
public override int GetHashCode()
```

### 戻り値

ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できる、現在のオブジェクトのハッシュコードです。

### 備考

このメソッドはGetHashCodeをオーバーライドします。ハッシュコードはオブジェクトの`Id`および`Name`プロパティを使用して計算されます。`unchecked`コンテキストはオーバーフローを許容し、ハッシュコード計算のコンテキストでは許容されます。

### 参照

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
