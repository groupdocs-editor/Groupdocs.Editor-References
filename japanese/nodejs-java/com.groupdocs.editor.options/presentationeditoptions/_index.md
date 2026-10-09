---
title: "PresentationEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポートされるすべてのプレゼンテーション（PowerPoint 互換）形式の文書を編集するためのカスタムオプションを指定できます。"
type: docs
weight: 32
url: /ja/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

サポート可能なすべてのドキュメント編集用にカスタムオプションを指定できます
プレゼンテーション（PowerPoint 互換）形式

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | 編集のために開くべきスライド番号を指定できます |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | 編集のために開くべきスライド番号を指定できます |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | 非表示スライドを含めるかどうかを指定します。 |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 非表示スライドを含めるかどうかを指定します。 |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


編集のために開くべきスライド番号を指定できます


*** ** * ** ***

スライド番号はスライドのゼロベースインデックスで、プレゼンテーションから編集対象の特定のスライドを指定・選択するために使用します。0 未満の場合は最初のスライドが選択されます（SlideNumber = 0 と同じです）。プレゼンテーション内のスライド総数より大きい場合は最後のスライドが選択されます。入力プレゼンテーションが単一スライドのみの場合、このオプションは無視され、そのスライドが編集されます。非表示スライドを編集しようとした場合で、ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) オプションが 'false' に設定されていると、例外がスローされます。

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


編集のために開くべきスライド番号を指定できます


*** ** * ** ***

スライド番号はスライドのゼロベースインデックスで、プレゼンテーションから編集対象の特定のスライドを指定・選択するために使用します。0 未満の場合は最初のスライドが選択されます（SlideNumber = 0 と同じです）。プレゼンテーション内のスライド総数より大きい場合は最後のスライドが選択されます。入力プレゼンテーションが単一スライドのみの場合、このオプションは無視され、そのスライドが編集されます。非表示スライドを編集しようとした場合で、ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) オプションが 'false' に設定されていると、例外がスローされます。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


非表示スライドを含めるかどうかを指定します。デフォルトは
false - 非表示スライドは表示されず、例外がスローされます
それらを編集しようとした場合。


**Returns:**
ブール
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


非表示スライドを含めるかどうかを指定します。デフォルトは
false - 非表示スライドは表示されず、例外がスローされます
それらを編集しようとした場合。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

