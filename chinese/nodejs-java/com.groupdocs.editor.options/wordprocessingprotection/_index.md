---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "封装从 HTML 生成的 WordProcessing 文档的保护选项。"
type: docs
weight: 46
url: /zh/nodejs-java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

封装 WordProcessing 文档的保护选项，
该文档是从 HTML 生成的

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | 无参数构造函数 - 所有参数都有默认值 |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | 允许在类实例化期间设置所有参数 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | 允许设置文档的保护类型。 |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | 允许设置文档的保护类型。 |
|
|  | [getPassword()](#getPassword--) | 用于保护文档的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 用于保护文档的密码。 |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


无参数构造函数 - 所有参数都有默认值


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


允许在类实例化期间设置所有参数


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | protectionType | int | 设置文档的保护类型 |
|
|  | 密码 | java.lang.String | 设置保护密码 |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


允许设置文档的保护类型。默认情况下设置为不
对文档进行任何保护。


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


允许设置文档的保护类型。默认情况下设置为不
对文档进行任何保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


用于保护文档的密码。如果为 null 或空字符串 - 则
保护将不会应用于文档。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


用于保护文档的密码。如果为 null 或空字符串 - 则
保护将不会应用于文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
