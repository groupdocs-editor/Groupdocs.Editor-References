---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许为所有受支持的 Presentation PowerPoint 兼容格式的文档编辑指定自定义选项"
type: docs
weight: 32
url: /zh/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

允许为编辑所有可支持的文档指定自定义选项
Presentation（PowerPoint 兼容）格式

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | 允许指定应打开进行编辑的幻灯片编号 |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | 允许指定应打开进行编辑的幻灯片编号 |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定是否应包含隐藏的幻灯片。 |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定是否应包含隐藏的幻灯片。 |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


允许指定应打开进行编辑的幻灯片编号


*** ** * ** ***

Slide number 是幻灯片的零基索引，允许指定并选择演示文稿中要编辑的特定幻灯片。如果小于 0，第一张幻灯片将被选中（等同于 SlideNumber = 0）。如果大于演示文稿中所有幻灯片的数量，最后一张幻灯片将被选中。如果输入的演示文稿仅包含单张幻灯片，此选项将被忽略，并编辑该单张幻灯片。如果尝试打开隐藏的幻灯片进行编辑，而  ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) 选项被设置为 'false'，将抛出异常。

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


允许指定应打开进行编辑的幻灯片编号


*** ** * ** ***

Slide number 是幻灯片的零基索引，允许指定并选择演示文稿中要编辑的特定幻灯片。如果小于 0，第一张幻灯片将被选中（等同于 SlideNumber = 0）。如果大于演示文稿中所有幻灯片的数量，最后一张幻灯片将被选中。如果输入的演示文稿仅包含单张幻灯片，此选项将被忽略，并编辑该单张幻灯片。如果尝试打开隐藏的幻灯片进行编辑，而  ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) 选项被设置为 'false'，将抛出异常。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


指定是否应包含隐藏的幻灯片。默认是
false - 隐藏的幻灯片不显示，并且在
尝试编辑它们时将抛出异常。


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


指定是否应包含隐藏的幻灯片。默认是
false - 隐藏的幻灯片不显示，并且在
尝试编辑它们时将抛出异常。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

