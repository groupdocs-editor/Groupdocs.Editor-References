---
title: "GetBodyContent"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "開閉 BODY タグの間にある HTML ドキュメントの内部コンテンツ本体を、タグ自体を除いた文字列として返します。"
type: docs
weight: 120
url: /ja/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

HTML ドキュメントの BODY タグの開始と終了の間の内部コンテンツ（タグ自体は除く）を文字列として返します

```csharp
public string GetBodyContent()
```

### 戻り値

開閉 BODY タグを除いた HTML ドキュメントの本体を含む文字列

### 備考

ほとんどの WYSIWYG エディタは通常、ドキュメントの BODY の内部コンテンツで操作し、HEAD ブロックからのメタ情報を正しく処理できません。このメソッドはそのようなケース向けに設計されています。このオーバーロードでは外部リソース要求の URI を調整することはできません。

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

HTML ドキュメントの BODY タグの開始と終了の間の内部コンテンツ（タグ自体は除く）を文字列として返します。外部リソースへのリンクは指定されたプレースホルダー付きテンプレートを含みます

```csharp
public string GetBodyContent(string externalImagesTemplate)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| externalImagesTemplate | 文字列 | このパラメーターを使用すると、1 つのプレースホルダーを持つ文字列テンプレートを指定でき、結果の HTML 文字列内の IMG 要素の外部画像へのリンクすべてに適用されます。NULL または空の場合、テンプレートは追加されず、純粋なファイル名のみが結果の HTML マークアップに残ります。テンプレートが無効な場合、プレフィックスとして扱われ、ファイル名はその末尾に連結されます。 |

### 戻り値

開閉 BODY タグを除いた HTML ドキュメントの本体を含む文字列で、外部画像に合わせて調整されたリンクが含まれます

### 備考

ほとんどのWYSIWYGエディタは通常、ドキュメントのBODY内部のコンテンツを操作し、HEADブロックからのメタ情報を正しく処理できません。このメソッドはそのようなケース向けに設計されており、このオーバーロードは外部リソース要求のURIを調整できるようにします。

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
