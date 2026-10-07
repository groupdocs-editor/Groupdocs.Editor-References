---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor for Java API 참조"
description: "HTML에서 생성된 WordProcessing 문서에 대한 문서 보호 옵션을 캡슐화합니다."
type: docs
weight: 46
url: /ko/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

WordProcessing 문서에 대한 문서 보호 옵션을 캡슐화합니다,
HTML에서 생성된

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | 매개변수가 없는 생성자 - 모든 매개변수는 기본값을 가집니다. |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | 클래스 인스턴스화 시 모든 매개변수를 설정할 수 있습니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | 문서의 보호 유형을 설정할 수 있습니다. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | 문서의 보호 유형을 설정할 수 있습니다. |
|
|  | [getPassword()](#getPassword--) | 문서를 보호하기 위한 비밀번호입니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 문서를 보호하기 위한 비밀번호입니다. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


매개변수가 없는 생성자 - 모든 매개변수는 기본값을 가집니다.


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


클래스 인스턴스화 시 모든 매개변수를 설정할 수 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | protectionType | int | 문서의 보호 유형을 설정합니다. |
|
|  | 비밀번호 | java.lang.String | 보호 비밀번호를 설정합니다 |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


문서의 보호 유형을 설정할 수 있습니다. 기본값은 보호하지 않음으로 설정됩니다
문서를 전혀 보호하지 않습니다.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


문서의 보호 유형을 설정할 수 있습니다. 기본값은 보호하지 않음으로 설정됩니다
문서를 전혀 보호하지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


문서를 보호하기 위한 비밀번호입니다. null이거나 빈 문자열인 경우 -
보호가 문서에 적용되지 않습니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


문서를 보호하기 위한 비밀번호입니다. null이거나 빈 문자열인 경우 -
보호가 문서에 적용되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
