---
title: "WordProcessingProtectionType"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "表示 WordProcessing 文档的所有可用保护类型。"
type: docs
weight: 47
url: /zh/nodejs-java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

表示 WordProcessing 文档的所有可用保护类型。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NoProtection](#NoProtection) | 文档未受保护。 |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | 用户只能向文档添加修订标记 |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | 用户只能修改文档中的批注 |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | 用户只能在文档的表单字段中输入数据 |
|
|  | [ReadOnly](#ReadOnly) | 不允许对文档进行更改 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


文档未受保护。默认值。


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


用户只能向文档添加修订标记


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


用户只能修改文档中的批注


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


用户只能在文档的表单字段中输入数据


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


不允许对文档进行更改


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
