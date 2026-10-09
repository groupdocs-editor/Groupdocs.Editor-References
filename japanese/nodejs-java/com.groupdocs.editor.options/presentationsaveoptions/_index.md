---
title: "PresentationSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PowerPoint 互換のプレゼンテーションドキュメントの生成および保存のためのカスタムオプションを指定できます"
type: docs
weight: 34
url: /ja/nodejs-java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

プレゼンテーションの生成および保存のためのカスタムオプションを指定できます
(PowerPoint 互換) ドキュメント

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | このパラメータなしコンストラクタは、PPTX 出力形式で PresentationSaveOptions の新しいインスタンスを作成します（その後、以下を通じて変更可能です） |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | 指定されたものを使用して PresentationSaveOptions の新しいインスタンスを作成します |
必須の Presentation 出力形式で、他のすべてのパラメータは
デフォルト
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | パスワードを指定、変更、取得でき、以下の目的で使用されます。 |
結果として得られる Presentation ドキュメントをエンコードします。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 結果として得られる Presentation ドキュメントのエンコードに使用されるパスワードを指定、変更、取得できます。 |
|
|  | [getSlideNumber()](#getSlideNumber--) | 新しい単一スライドのプレゼンテーションを作成する代わりに、編集されたスライドを既存のプレゼンテーションに挿入できます（デフォルトの動作）。 |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | 新しい単一スライドのプレゼンテーションを作成する代わりに、編集されたスライドを既存のプレゼンテーションに挿入できます（デフォルトの動作）。 |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | ブールフラグで、編集されたスライドが元のプレゼンテーションの指定された位置にある既存のスライドを置き換えるかどうかを指定します。 |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) プロパティ、または既存のスライドと前のスライドの間に挿入され、内容は置き換えられません。
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | ブールフラグで、編集されたスライドが元のプレゼンテーションの指定された位置にある既存のスライドを置き換えるかどうかを指定します。 |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) プロパティ、または既存のスライドと前のスライドの間に挿入され、内容は置き換えられません。
|
|  | [getOutputFormat()](#getOutputFormat--) | ドキュメントの保存に使用される Presentation 形式を指定できます |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | ドキュメントの保存に使用される Presentation 形式を指定できます |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | 編集されたスライドが既存のプレゼンテーションに挿入される場合に、保存中にプレゼンテーションから削除すべきスライドの 1 ベース番号の配列を指定できます。 |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | 編集されたスライドが既存のプレゼンテーションに挿入される場合に、保存中にプレゼンテーションから削除すべきスライドの 1 ベース番号の配列を指定できます。 |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


このパラメータなしコンストラクタは、PPTX 出力形式で PresentationSaveOptions の新しいインスタンスを作成します（その後、以下を通じて変更可能です）
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


指定されたものを使用して PresentationSaveOptions の新しいインスタンスを作成します
必須の Presentation 出力形式で、他のすべてのパラメータは
デフォルト


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Presentation ドキュメントを保存すべき必須の出力形式 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワードを指定、変更、取得でき、以下の目的で使用されます。
結果として得られる Presentation ドキュメントをエンコードします。デフォルトは NULL です -
パスワードは設定されません。削除するには NULL または空文字列に設定してください
以前に設定されていた場合はパスワードを削除します。


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


結果として得られる Presentation ドキュメントのエンコードに使用されるパスワードを指定、変更、取得できます。
デフォルトは NULL で、パスワードは設定されません。以前に設定されていた場合は、パスワードを削除するために NULL または空文字列に設定してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


新しい単一スライドのプレゼンテーションを作成する代わりに、編集されたスライドを既存のプレゼンテーションに挿入できます（デフォルトの動作）。
スライド番号は、Editor クラスでロードされたプレゼンテーション内のスライドの 1 ベース番号です。0（デフォルト値）の場合、新しいプレゼンテーションは単一の編集スライドで作成されます。0 より大きいまたは小さい場合で、Editor クラスで有効なプレゼンテーションがロードされていると、入力の EditableDocument インスタンスに格納された編集スライドがこのプレゼンテーションに挿入されます。

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


新しい単一スライドのプレゼンテーションを作成する代わりに、編集されたスライドを既存のプレゼンテーションに挿入できます（デフォルトの動作）。
スライド番号は、Editor クラスでロードされたプレゼンテーション内のスライドの 1 ベース番号です。0（デフォルト値）の場合、新しいプレゼンテーションは単一の編集スライドで作成されます。0 より大きいまたは小さい場合で、Editor クラスで有効なプレゼンテーションがロードされていると、入力の EditableDocument インスタンスに格納された編集スライドがこのプレゼンテーションに挿入されます。

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


ブールフラグで、編集されたスライドが元のプレゼンテーションの指定された位置にある既存のスライドを置き換えるかどうかを指定します。
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) プロパティ、または既存のスライドと前のスライドの間に挿入され、内容は置き換えられません。
デフォルトは false — 既存のスライドが置き換えられます。このプロパティは、値が
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) プロパティが '0' に設定されている場合。

<br />

*** ** * ** ***

デフォルトではスライドは置き換えられます。つまり、対象のプレゼンテーションに 5 枚のスライドがあり、SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 の場合、4 番目のスライドは新しい編集スライドで置き換えられ、プレゼンテーションの総スライド数 (5) は変わりません。ただし、このプロパティの値が *true* に設定されている場合、新しい編集スライドは 4 番目のスライドとして挿入され、以降のスライドはすべて末尾へシフトします。"old" の 4 番目のスライドは 5 番目になり、5 番目は 6 番目になり、プレゼンテーションの総スライド数は 1 増えて 6 になります。

<br />



**Returns:**
ブール
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


ブールフラグで、編集されたスライドが元のプレゼンテーションの指定された位置にある既存のスライドを置き換えるかどうかを指定します。
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) プロパティ、または既存のスライドと前のスライドの間に挿入され、内容は置き換えられません。
デフォルトは false — 既存のスライドが置き換えられます。このプロパティは、値が
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) プロパティが '0' に設定されている場合。

<br />

*** ** * ** ***

デフォルトではスライドは置き換えられます。つまり、対象のプレゼンテーションに 5 枚のスライドがあり、SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 の場合、4 番目のスライドは新しい編集スライドで置き換えられ、プレゼンテーションの総スライド数 (5) は変わりません。ただし、このプロパティの値が *true* に設定されている場合、新しい編集スライドは 4 番目のスライドとして挿入され、以降のスライドはすべて末尾へシフトします。"old" の 4 番目のスライドは 5 番目になり、5 番目は 6 番目になり、プレゼンテーションの総スライド数は 1 増えて 6 になります。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


ドキュメントの保存に使用される Presentation 形式を指定できます

<br />

*** ** * ** ***

出力形式は通常、このクラスのコンストラクタで設定されます。これは必須だからです。このプロパティにより、[PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) クラスのインスタンスがすでに作成されている場合でも、後で出力形式を取得または変更できます。

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


ドキュメントの保存に使用される Presentation 形式を指定できます

<br />

*** ** * ** ***

出力形式は通常、このクラスのコンストラクタで設定されます。これは必須だからです。このプロパティにより、[PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) クラスのインスタンスがすでに作成されている場合でも、後で出力形式を取得または変更できます。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


プレゼンテーションの保存時に、削除すべきスライドの 1 ベース番号の配列を指定できるようにします（編集されたスライドが既存のプレゼンテーションに挿入される場合）。編集されたスライドが新しい単一スライドのプレゼンテーションとして保存されるのではなく（既定の動作）、既存のプレゼンテーションに保存される場合（#getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int) を使用）、この配列で番号を指定することにより、特定のスライドを削除することも可能です。デフォルトではこの配列は  null  \\u2014 スライドは削除されません。ただし、この配列が null でなく、かつ空でなく、少なくとも 1 つの有効なスライド番号を含む場合、編集されたスライドの内容で出力プレゼンテーション文書が生成された後、指定された番号のスライドは、出力ストリームまたはファイルに書き込む直前にプレゼンテーションから削除されます。この配列のスライド番号は 1 ベースであり、0 ベースではありません。無効な番号（1 未満または総スライド数を超えるもの）は無視されます。


**Returns:**
int[] - 削除する 1 ベースのスライド番号の配列、または何も削除しない場合は  null  。

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


編集されたスライドが既存のプレゼンテーションに挿入される場合に、保存時に削除すべきスライドの 1 ベース番号の配列を指定できます。この配列のスライド番号は 1 ベースです。無効な番号は無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int[] | 削除する 1 ベースのスライド番号の配列（  null  または空でもかまいません）。 |
|

