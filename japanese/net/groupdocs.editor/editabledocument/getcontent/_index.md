---
title: "GetContent"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定されたテキストエンコーディングでこの内容を指定されたストリームに書き込むことにより、HTML ドキュメント全体の内容をバイトストリームとして返します"
type: docs
weight: 130
url: /ja/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

指定されたテキストエンコーディングでこの内容を指定されたストリームに書き込むことにより、HTML ドキュメント全体の内容をバイトストリームとして返します

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| パラメーター | 説明 |
| --- | --- |
| TStream | Streamの任意の実装 |
| storage | 書き込みをサポートする、nullでないバイトストリーム |
| encoding | 指定された*storage*にテキストコンテンツを書き込む際に適用すべき、nullでないテキストエンコーディング |

### 戻り値

指定された*storage*のインスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | 入力引数のいずれかがnullです |
| ArgumentException | 指定されたストリームは書き込み可能ではありません |

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

HTML ドキュメント全体の内容を文字列として返します

```csharp
public string GetContent()
```

### 戻り値

HTMLドキュメントの内容を含む文字列

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

HTML ドキュメント全体の内容を文字列として返します。外部リソースへのリンクは指定されたプレースホルダー付きテンプレートを含みます

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| externalImagesTemplate | 文字列 | このパラメーターを使用すると、1 つのプレースホルダーを持つ文字列テンプレートを指定でき、結果の HTML 文字列内の IMG 要素の外部画像へのリンクすべてに適用されます。NULL または空の場合、テンプレートは追加されず、純粋なファイル名のみが結果の HTML マークアップに残ります。テンプレートが無効な場合、プレフィックスとして扱われ、ファイル名はその末尾に連結されます。 |
| externalCssTemplate | 文字列 | このパラメータを使用すると、1つのプレースホルダーを持つ文字列テンプレートを指定でき、結果のHTML文字列に含まれるLINK要素のすべての外部スタイルシートへのリンクに追加されます。NULLまたは空の場合、テンプレートは追加されず、純粋なファイル名のみが結果のHTMLマークアップに表示されます。テンプレートが無効な場合はプレフィックスとして扱われ、ファイル名はその末尾に連結されます。 |

### 戻り値

外部リソースに合わせて調整されたリンク付きHTMLドキュメントの内容を含む文字列

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
