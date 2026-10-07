---
title: "WordProcessingProtectionType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "WordProcessing 문서의 모든 사용 가능한 보호 유형을 나타냅니다."
type: docs
weight: 47
url: /ko/java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

WordProcessing 문서의 모든 사용 가능한 보호 유형을 나타냅니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NoProtection](#NoProtection) | 문서는 보호되지 않았습니다. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | 사용자는 문서에 수정 표시만 추가할 수 있습니다. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | 사용자는 문서의 주석만 수정할 수 있습니다. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | 사용자는 문서의 양식 필드에만 데이터를 입력할 수 있습니다. |
|
|  | [ReadOnly](#ReadOnly) | 문서에 대한 변경이 허용되지 않습니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


문서는 보호되지 않았습니다. 기본값.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


사용자는 문서에 수정 표시만 추가할 수 있습니다.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


사용자는 문서의 주석만 수정할 수 있습니다.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


사용자는 문서의 양식 필드에만 데이터를 입력할 수 있습니다.


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


문서에 대한 변경이 허용되지 않습니다.


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
