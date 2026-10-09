---
title: "TextDirection"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示在纯文本文档中处理文本方向的 3 种可能变体"
type: docs
weight: 38
url: /zh/nodejs-java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

表示在纯文本中处理文本方向的 3 种可能变体
文档

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | 从左到右方向，常规文本，默认值。 |
|
|  | [RightToLeft](#RightToLeft) | 从右到左方向 |
|
|  | [Auto](#Auto) | 自动检测方向。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


从左到右方向，常规文本，默认值。


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


从右到左方向


### Auto {#Auto}
```
public static final int Auto
```


自动检测方向。当选择此选项且文本包含
属于 RTL 脚本的字符时，文档方向将被设置为
自动 RTL。


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
