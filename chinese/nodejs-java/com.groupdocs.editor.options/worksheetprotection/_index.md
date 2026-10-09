---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "封装工作表保护选项，允许使用指定密码保护输出的 Spreadsheet 文档中的工作表，防止指定类型的修改。"
type: docs
weight: 49
url: /zh/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

封装工作表保护选项，允许保护工作表
在输出的 Spreadsheet 文档中防止指定类型的修改，使用
指定的密码。


*** ** * ** ***

大多数 Spreadsheet 格式（如 XLSX）允许使用密码保护工作表不被编辑。此类允许启用此类保护并指定其选项。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | 使用默认参数创建新实例。 |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | 创建具有指定工作表保护类型的新实例并 |
密码
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | 允许指定工作表保护的类型。 |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | 允许指定工作表保护的类型。 |
|
|  | [getPassword()](#getPassword--) | 密码，用于保护工作表。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 密码，用于保护工作表。 |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


使用默认参数创建新实例。如果未修改并传递
到 SpreadsheetSaveOptions，将不会应用工作表保护


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


创建具有指定工作表保护类型的新实例并
密码


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | protectionType | int | 工作表保护的类型 |
|
|  | 密码 | java.lang.String | 密码，用于锁定保护 |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


允许指定工作表保护的类型。默认是 'None' -
未应用保护。


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


允许指定工作表保护的类型。默认是 'None' -
未应用保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


密码，用于保护工作表。如果为 NULL 或为空
字符串，则不会应用保护。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


密码，用于保护工作表。如果为 NULL 或为空
字符串，则不会应用保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

