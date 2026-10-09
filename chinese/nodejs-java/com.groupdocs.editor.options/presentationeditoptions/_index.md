---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许为所有受支持的演示 PowerPoint 兼容格式的文档编辑指定自定义选项"
type: docs
weight: 32
url: /zh/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

允许为所有支持的文档指定自定义编辑选项
演示（PowerPoint 兼容）格式

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

幻灯片编号是幻灯片的零基索引，允许在演示文稿中指定并选择要编辑的特定幻灯片。如果小于 0，则选择第一张幻灯片（等同于 SlideNumber = 0）。如果大于演示文稿中所有幻灯片的数量，则选择最后一张幻灯片。如果输入的演示文稿仅包含单张幻灯片，则此选项将被忽略，并编辑该唯一幻灯片。如果尝试在编辑时打开隐藏的幻灯片，而 ShowHiddenSlides（#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)）选项设置为 'false'，则会抛出异常。

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


允许指定应打开进行编辑的幻灯片编号


*** ** * ** ***

幻灯片编号是幻灯片的零基索引，允许在演示文稿中指定并选择要编辑的特定幻灯片。如果小于 0，则选择第一张幻灯片（等同于 SlideNumber = 0）。如果大于演示文稿中所有幻灯片的数量，则选择最后一张幻灯片。如果输入的演示文稿仅包含单张幻灯片，则此选项将被忽略，并编辑该唯一幻灯片。如果尝试在编辑时打开隐藏的幻灯片，而 ShowHiddenSlides（#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)）选项设置为 'false'，则会抛出异常。

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
尝试编辑它们时会抛出异常。


**Returns:**
布尔
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


指定是否应包含隐藏的幻灯片。默认是
false - 隐藏的幻灯片不显示，并且在
尝试编辑它们时会抛出异常。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

