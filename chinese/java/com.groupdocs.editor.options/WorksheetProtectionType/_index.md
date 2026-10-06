---
title: "WorksheetProtectionType"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示电子表格工作表选项卡保护类型"
type: docs
weight: 50
url: /zh/java/com.groupdocs.editor.options/worksheetprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtectionType
```

表示 Spreadsheet 工作表（标签）保护类型。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [None](#None) | 未应用保护（默认值） |
|
|  | [All](#All) | 用户无法修改工作表上的任何内容 |
|
|  | [Contents](#Contents) | 用户无法在工作表中输入数据 |
|
|  | [Objects](#Objects) | 用户无法修改绘图对象 |
|
|  | [Scenarios](#Scenarios) | 用户无法修改已保存的方案 |
|
|  | [Structure](#Structure) | 用户无法修改结构 |
|
|  | [Window](#Window) | 用户无法修改窗口 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAll()](#getAll--) |  |
### None {#None}
```
public static final int None
```


未应用保护（默认值）


### All {#All}
```
public static final int All
```


用户无法修改工作表上的任何内容


### Contents {#Contents}
```
public static final int Contents
```


用户无法在工作表中输入数据


### Objects {#Objects}
```
public static final int Objects
```


用户无法修改绘图对象


### Scenarios {#Scenarios}
```
public static final int Scenarios
```


用户无法修改已保存的方案


### Structure {#Structure}
```
public static final int Structure
```


用户无法修改结构


### Window {#Window}
```
public static final int Window
```


用户无法修改窗口


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
