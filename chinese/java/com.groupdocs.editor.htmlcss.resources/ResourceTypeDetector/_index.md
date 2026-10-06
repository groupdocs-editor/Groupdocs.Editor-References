---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor for Java API 参考"
description: "用于检测资源类型和格式的实用静态方法"
type: docs
weight: 10
url: /zh/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

用于检测资源类型（格式）的实用静态方法。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | 从指定的文件名检测类型并返回一个实例 |
相应的 IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | 尝试分析输入流并创建一个支持的 HTML |
资源，从中考虑指定的假设类型，如果它
不为 null
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


从指定的文件名检测类型并返回一个实例
相应的 IResourceType


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件名 | java.lang.String | 输入文件名，方法将尝试从中提取结果 IResourceType 实现 |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


尝试分析输入流并创建一个支持的 HTML
资源，从中考虑指定的假设类型，如果它
不为 null


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | 输入流，可能包含 HTML 资源。如果无效，将抛出异常。 |
|
|  | 名称 | java.lang.String | 资源名称，将用于成功时创建和返回的资源。不能为空、空字符串或仅空白 |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | 假定的输入 HTML 资源格式，有助于实现最佳性能。如果完全未知，请使用 NULL 值。可能不正确，这只会降低性能。 |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

