---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许指定用于生成和保存兼容 PowerPoint 的演示文稿的自定义选项"
type: docs
weight: 34
url: /zh/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

允许指定用于生成和保存演示文稿的自定义选项
（兼容 PowerPoint）文档

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | 此无参构造函数创建一个使用 PPTX 输出格式的 PresentationSaveOptions 新实例（随后可通过以下方式修改 |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | 使用指定的 |
必需的演示文稿输出格式，而所有其他参数则是
默认
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改并获取将用于 |
对生成的演示文稿进行编码。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改和获取用于对生成的演示文稿进行编码的密码。 |
|
|  | [getSlideNumber()](#getSlideNumber--) | 允许将编辑后的幻灯片插入现有演示文稿，而不是创建新的单幻灯片演示文稿（默认行为）。 |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | 允许将编辑后的幻灯片插入现有演示文稿，而不是创建新的单幻灯片演示文稿（默认行为）。 |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | 布尔标志，指定编辑后的幻灯片是否应在原始演示文稿中由以下位置指定的位置替换现有幻灯片， |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 属性，或者应将其插入到现有幻灯片与前一幻灯片之间，而不替换其内容。
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | 布尔标志，指定编辑后的幻灯片是否应在原始演示文稿中由以下位置指定的位置替换现有幻灯片， |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 属性，或者应将其插入到现有幻灯片与前一幻灯片之间，而不替换其内容。
|
|  | [getOutputFormat()](#getOutputFormat--) | 允许指定用于保存文档的演示文稿格式 |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | 允许指定用于保存文档的演示文稿格式 |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | 允许指定一个数组，其中包含在保存期间应从演示文稿中删除的幻灯片的基于 1 的编号，适用于将编辑后的幻灯片插入现有演示稿的情况。 |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | 允许指定一个数组，其中包含在保存期间应从演示文稿中删除的幻灯片的基于 1 的编号，适用于将编辑后的幻灯片插入现有演示稿的情况。 |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


此无参构造函数创建一个使用 PPTX 输出格式的 PresentationSaveOptions 新实例（随后可通过以下方式修改
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


使用指定的
必需的演示文稿输出格式，而所有其他参数则是
默认


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | 必须的输出格式，用于保存演示文稿 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改并获取将用于
对生成的演示文稿进行编码。默认情况下为 NULL -
密码将不会被设置。将其设为 NULL 或空字符串以移除。
密码，如果之前已设置的话。


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改和获取用于对生成的演示文稿进行编码的密码。
默认情况下为 NULL \\u2014 密码不会被设置。如果之前已设置密码，需将其设为 NULL 或空字符串以移除密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


允许将编辑后的幻灯片插入现有演示文稿，而不是创建新的单幻灯片演示文稿（默认行为）。
Slide number 是演示文稿中幻灯片的基于 1 的编号，演示文稿已在 Editor 类中加载。如果其为 0（默认值），将创建仅包含单个编辑幻灯片的新演示文稿。如果其大于或小于零，并且 Editor 类中已加载有效的演示文稿，则存储在输入 EditableDocument 实例中的编辑幻灯片将被插入到该演示文稿中。

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


允许将编辑后的幻灯片插入现有演示文稿，而不是创建新的单幻灯片演示文稿（默认行为）。
Slide number 是演示文稿中幻灯片的基于 1 的编号，演示文稿已在 Editor 类中加载。如果其为 0（默认值），将创建仅包含单个编辑幻灯片的新演示文稿。如果其大于或小于零，并且 Editor 类中已加载有效的演示文稿，则存储在输入 EditableDocument 实例中的编辑幻灯片将被插入到该演示文稿中。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


布尔标志，指定编辑后的幻灯片是否应在原始演示文稿中由以下位置指定的位置替换现有幻灯片，
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 属性，或者应将其插入到现有幻灯片与前一幻灯片之间，而不替换其内容。
默认情况下为 false \\u2014 现有幻灯片将被替换。如果该属性的值为
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 属性被设置为 '0'。

<br />

*** ** * ** ***

默认情况下幻灯片会被替换。这意味着如果给定的演示文稿有 5 张幻灯片，且 SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4，则第 4 张幻灯片将被新的编辑幻灯片替换，而演示文稿的总幻灯片数（5）保持不变。然而，如果该属性的值被设置为 *true*，新的编辑幻灯片将作为第 4 张幻灯片插入，所有后续幻灯片将向后移动：\"old\" 第 4 张幻灯片变为第 5 张，第 5 张变为第 6 张，演示文稿的总幻灯片数将增加一张，变为 6。

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


布尔标志，指定编辑后的幻灯片是否应在原始演示文稿中由以下位置指定的位置替换现有幻灯片，
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 属性，或者应将其插入到现有幻灯片与前一幻灯片之间，而不替换其内容。
默认情况下为 false \\u2014 现有幻灯片将被替换。如果该属性的值为
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 属性被设置为 '0'。

<br />

*** ** * ** ***

默认情况下幻灯片会被替换。这意味着如果给定的演示文稿有 5 张幻灯片，且 SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4，则第 4 张幻灯片将被新的编辑幻灯片替换，而演示文稿的总幻灯片数（5）保持不变。然而，如果该属性的值被设置为 *true*，新的编辑幻灯片将作为第 4 张幻灯片插入，所有后续幻灯片将向后移动：\"old\" 第 4 张幻灯片变为第 5 张，第 5 张变为第 6 张，演示文稿的总幻灯片数将增加一张，变为 6。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


允许指定用于保存文档的演示文稿格式

<br />

*** ** * ** ***

输出格式通常在此类的构造函数中设置，因为它是必需的。该属性允许在已创建 [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) 类的实例后，获取或修改输出格式。

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


允许指定用于保存文档的演示文稿格式

<br />

*** ** * ** ***

输出格式通常在此类的构造函数中设置，因为它是必需的。该属性允许在已创建 [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) 类的实例后，获取或修改输出格式。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


允许指定一个数组，其中包含在保存演示文稿时应删除的幻灯片的基于 1 的编号，前提是编辑幻灯片被插入到已有演示文稿中。当编辑幻灯片不是保存为新的单幻灯片演示文稿（默认行为），而是保存到已有演示文稿中（使用 #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)）时，也可以通过在此数组中指定编号来删除该演示文稿中的特定幻灯片。默认情况下此数组为 null \\u2014 不会删除任何幻灯片。然而，当此数组非 null 且非空，并且至少包含一个有效的幻灯片编号时，在生成包含编辑幻灯片内容的输出 Presentation 文档后，这些指定编号的幻灯片将在写入输出流或文件之前被删除。此数组中的幻灯片编号是基于 1 的，而非基于 0 的。无效的编号（小于 1 或大于幻灯片总数）将被忽略。


**Returns:**
int[] - 要删除的基于 1 的幻灯片编号数组，若不删除任何内容则为 null。

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


允许指定一个数组，其中包含在保存演示文稿时应删除的基于 1 的幻灯片编号，前提是编辑幻灯片被插入到已有演示文稿中。此数组中的幻灯片编号为基于 1 的。无效的编号将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 要删除的基于 1 的幻灯片编号数组（可为 null 或为空）。 |
|

