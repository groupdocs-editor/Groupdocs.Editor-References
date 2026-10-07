---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "PDF Portable Document Format 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정하도록 허용합니다"
type: docs
weight: 31
url: /ko/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

생성 및 저장을 위한 사용자 지정 옵션을 지정하도록 허용합니다 PDF (Portable
Document Format) 문서

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 생성된 PDF 문서에 사용자 비밀번호로 적용되는 비밀번호이며, 열기 위해 필요합니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 생성된 PDF 문서에 사용자 비밀번호로 적용되는 비밀번호이며, 열기 위해 필요합니다. |
|
|  | [getCompliance()](#getCompliance--) | 출력 문서에 대한 PDF 표준 준수 수준을 지정합니다. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | 출력 문서에 대한 PDF 표준 준수 수준을 지정합니다. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | 원본 문서에서 사용된 글꼴 리소스를 결과 PDF 문서에 삽입하는 역할을 합니다. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | 원본 문서에서 사용된 글꼴 리소스를 결과 PDF 문서에 삽입하는 역할을 합니다. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


생성된 PDF 문서에 사용자 비밀번호로 적용되는 비밀번호이며, 열기 위해 필요합니다.
NULL이거나 비어 있으면 문서에 비밀번호가 적용되지 않습니다. 그렇지 않으면 문서는 RC4(키 길이 128비트)로 암호화됩니다.
기본값은 NULL \\u2014 비밀번호가 적용되지 않습니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


생성된 PDF 문서에 사용자 비밀번호로 적용되는 비밀번호이며, 열기 위해 필요합니다.
NULL이거나 비어 있으면 문서에 비밀번호가 적용되지 않습니다. 그렇지 않으면 문서는 RC4(키 길이 128비트)로 암호화됩니다.
기본값은 NULL \\u2014 비밀번호가 적용되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


출력 문서에 대한 PDF 표준 준수 수준을 지정합니다. 기본값은 PdfCompliance.Pdf17입니다.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


출력 문서에 대한 PDF 표준 준수 수준을 지정합니다. 기본값은 PdfCompliance.Pdf17입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


원본 문서에서 사용된 글꼴 리소스를 결과 PDF 문서에 포함시키는 역할을 합니다. 기본값은 어떤 글꼴도 포함하지 않습니다(NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


원본 문서에서 사용된 글꼴 리소스를 결과 PDF 문서에 포함시키는 역할을 합니다. 기본값은 어떤 글꼴도 포함하지 않습니다(NotEmbed).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다.
이 옵션을 true로 설정하면 저장 시간이 느려지는 대가로 대용량 문서를 생성할 때 메모리 사용량을 크게 줄일 수 있습니다.
기본값은 false이며, 더 나은 성능을 위해 메모리 최적화가 비활성화됩니다.


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다.
이 옵션을 true로 설정하면 저장 시간이 느려지는 대가로 대용량 문서를 생성할 때 메모리 사용량을 크게 줄일 수 있습니다.
기본값은 false이며, 더 나은 성능을 위해 메모리 최적화가 비활성화됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

