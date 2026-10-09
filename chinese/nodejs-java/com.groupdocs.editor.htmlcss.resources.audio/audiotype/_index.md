---
title: "AudioType"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示一种受支持的音频类型格式"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

表示一种受支持的音频类型（格式）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | 此音频格式的正式名称 |
|
|  | [getFileExtension()](#getFileExtension--) | 此音频格式的文件扩展名（不含点字符） |
|
|  | [getMimeCode()](#getMimeCode--) | 此音频格式的 MIME 代码 |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 确定此实例是否与指定的 "AudioType" 实例相等 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例是否与指定的未转换对象相等，该对象可能是另一个 "AudioType" 实例 |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 检查两个 "AudioType" 值是否相等 |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 检查两个 "AudioType" 值是否不相等 |
|
|  | [hashCode()](#hashCode--) | 返回哈希码，该哈希码是此特定值类型的常数 |
|
|  | [getUndefined()](#getUndefined--) | 特殊值，用于标记未定义、未知或不受支持的音频格式 |
|
|  | [getMp3()](#getMp3--) | 表示 MPEG-1 Audio Layer III 音频格式 |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 返回 AudioType 值，该值等同于从指定文件名提取的文件扩展名 |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


此音频格式的正式名称


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


此音频格式的文件扩展名（不含点字符）


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


此音频格式的 MIME 代码


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


确定此实例是否与指定的 "AudioType" 实例相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 要与此进行比较的其他 AudioType 实例 |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例是否与指定的未转换对象相等，该对象可能是另一个 "AudioType" 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 另一个实例，可能是 AudioType 结构体，已装箱为 System.Object |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


检查两个 "AudioType" 值是否相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 要检查的第一个 AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 要检查的第二个 AudioType |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


检查两个 "AudioType" 值是否不相等


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 要检查的第一个 AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 要检查的第二个 AudioType |
|

**Returns:**
布尔值 - 相等则为 True，不相等则为 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回哈希码，该哈希码是此特定值类型的常数


**Returns:**
int - 4 字节有符号整数，0 表示未定义值

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


特殊值，用于标记未定义、未知或不受支持的音频格式


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


表示 MPEG-1 Audio Layer III 音频格式


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


返回 AudioType 值，该值等同于从指定文件名提取的文件扩展名


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件名 | java.lang.String | 任意文件名，可以是相对路径或完整路径 |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

