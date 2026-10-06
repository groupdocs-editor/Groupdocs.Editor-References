---
title: "ICssDataType"
second_title: "GroupDocs.Editor for Java API 参考"
description: "所有在 CSS 属性中使用的 CSS 数据类型的公共接口"
type: docs
weight: 15
url: /zh/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

所有用于 CSS 属性的 CSS 数据类型的通用接口。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | 应返回当前值的默认字符串表示 |
数据类型
|
|  | [isDefault()](#isDefault--) | 应定义数据类型的当前值是否为默认值 |
针对该特定数据类型的值是否为默认
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


应返回当前值的默认字符串表示
数据类型


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


应定义数据类型的当前值是否为默认值
针对该特定数据类型的值是否为默认


**Returns:**
boolean -
