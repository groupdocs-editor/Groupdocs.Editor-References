---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示表单字段的集合。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

表示表单字段的集合。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | 初始化 [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | 向集合中插入一个表单字段。 |
|
|  | [get(String name)](#get-java.lang.String-) | 获取具有指定名称的表单字段。 |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | 获取具有指定名称和类型的表单字段。 |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


初始化 [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) 类的新实例。


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


返回一个遍历集合的枚举器。


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - 可用于遍历集合的枚举器。

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


向集合中插入一个表单字段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | 要插入的表单字段。 |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


获取具有指定名称的表单字段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段的名称。 |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


获取具有指定名称和类型的表单字段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 表单字段的名称。 |


T
：表单字段的类型。
|
| 类型 | java.lang.Class<T> |  |

**Returns:**
T - 如果找到，则为具有指定名称和类型的表单字段；否则，为该类型的默认值。

