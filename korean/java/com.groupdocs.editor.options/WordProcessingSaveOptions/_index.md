---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "편집된 후 WordProcessing 호환 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 48
url: /ko/java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

생성 및 저장을 위한 사용자 지정 옵션을 지정할 수 있습니다.
편집된 후 WordProcessing 호환 문서


*** ** * ** ***

WordProcessingSaveOptions는 편집된 문서 내용을 포함하는 EditableDocument 클래스의 인스턴스가 존재하고, 해당 내용을 WordProcessing 형식의 새 문서로 저장해야 하는 상황에 적용됩니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | 이 매개변수 없는 생성자는 DOCX 출력 형식으로 WordProcessingSaveOptions의 새 인스턴스를 생성합니다(그 후에 수정할 수 있음). |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) 속성)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | 지정된 옵션으로 WordProcessingSaveOptions의 새 인스턴스를 생성합니다 |
필수 WordProcessing 출력 형식을 지정하고, 다른 모든 매개변수는
기본값
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 저장에 사용될 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
문서.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 저장에 사용될 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
문서.
|
|  | [getPassword()](#getPassword--) | 비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는 |
생성된 WordProcessing 문서를 인코딩하는 데 사용됩니다.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는 |
생성된 WordProcessing 문서를 인코딩하는 데 사용됩니다.
|
|  | [getOutputFormat()](#getOutputFormat--) | 저장에 사용될 WordProcessing 형식을 지정할 수 있습니다. |
문서
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | 저장에 사용될 WordProcessing 형식을 지정할 수 있습니다. |
문서
|
|  | [getLocale()](#getLocale--) | WordProcessing에 대한 기본 로케일(언어)을 재정의하도록 설정할 수 있습니다. |
문서이며, 생성 중에 적용됩니다.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | WordProcessing에 대한 기본 로케일(언어)을 재정의하도록 설정할 수 있습니다. |
문서이며, 생성 중에 적용됩니다.
|
|  | [getLocaleBi()](#getLocaleBi--) | WordProcessing 문서에 대한 로케일(언어)을 재정의하도록 설정할 수 있습니다. |
RTL(오른쪽에서 왼쪽) 텍스트에 대해, 이는
생성 시 적용됩니다.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | WordProcessing 문서에 대한 로케일(언어)을 재정의하도록 설정할 수 있습니다. |
RTL(오른쪽에서 왼쪽) 텍스트에 대해, 이는
생성 시 적용됩니다.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | WordProcessing 문서에 대한 로케일(언어)을 재정의할 수 있습니다. |
동아시아 텍스트에 대해, 이는 생성 중에 적용됩니다.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | WordProcessing 문서에 대한 로케일(언어)을 재정의할 수 있습니다. |
동아시아 텍스트에 대해, 이는 생성 중에 적용됩니다.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 문서 생성을 위해 HTML에서 메모리 최적화 메커니즘을 활성화합니다. |
이는 메모리 사용량 감소를 대가로 성능을 저하시킵니다.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 문서 생성을 위해 HTML에서 메모리 최적화 메커니즘을 활성화합니다. |
이는 메모리 사용량 감소를 대가로 성능을 저하시킵니다.
|
|  | [getProtection()](#getProtection--) | 문서 보호 옵션을 제어하고 적용할 수 있습니다. |
어떤 형식이든 지원하는 WordProcessing 문서에 대해, 이는 문서
보호를 지원합니다.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | 문서 보호 옵션을 제어하고 적용할 수 있습니다. |
어떤 형식이든 지원하는 WordProcessing 문서에 대해, 이는 문서
보호를 지원합니다.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | 출력 WordProcessing에 글꼴 리소스를 포함시키는 역할을 합니다. |
문서.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | 출력 WordProcessing에 글꼴 리소스를 포함시키는 역할을 합니다. |
문서.
|
|  | [deepClone()](#deepClone--) | 이 인스턴스의 전체 복사본을 생성하고 반환합니다. |
WordProcessingSaveOptions 클래스
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


이 매개변수 없는 생성자는 DOCX 출력 형식으로 WordProcessingSaveOptions의 새 인스턴스를 생성합니다(그 후에 수정할 수 있음).
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) 속성)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


지정된 옵션으로 WordProcessingSaveOptions의 새 인스턴스를 생성합니다
필수 WordProcessing 출력 형식을 지정하고, 다른 모든 매개변수는
기본값


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | WordProcessing 문서를 저장해야 하는 필수 출력 형식 |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


저장에 사용될 페이지 매김을 활성화하거나 비활성화할 수 있습니다.
문서. 원본 문서가 페이지 매김 모드에서 열리고 편집된 경우
이 옵션도 활성화되어야 합니다. 기본값은 비활성화되어 있습니다.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


저장에 사용될 페이지 매김을 활성화하거나 비활성화할 수 있습니다.
문서. 원본 문서가 페이지 매김 모드에서 열리고 편집된 경우
이 옵션도 활성화되어야 합니다. 기본값은 비활성화되어 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는
생성된 WordProcessing 문서를 인코딩하는 데 사용됩니다. NULL 또는
비밀번호를 제거(정리)하려면 빈 문자열을 지정합니다.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


비밀번호를 지정, 수정, 획득 또는 제거할 수 있으며, 이는
생성된 WordProcessing 문서를 인코딩하는 데 사용됩니다. NULL 또는
비밀번호를 제거(정리)하려면 빈 문자열을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


저장에 사용될 WordProcessing 형식을 지정할 수 있습니다.
문서


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


저장에 사용될 WordProcessing 형식을 지정할 수 있습니다.
문서


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


WordProcessing에 대한 기본 로케일(언어)을 재정의하도록 설정할 수 있습니다.
문서이며, 생성 중에 적용됩니다. 지정되지 않은 경우
지정된 (기본값), MS Word(또는 다른 프로그램)는 감지(또는
선택) 문서 로케일을 자체 설정 또는 기타
요소에 따라 결정합니다.


*** ** * ** ***

이 옵션은 지정된 로케일을 문서의 전체 텍스트에 강제로 적용합니다. 문서에 서로 다른 언어로 작성된 다양한 텍스트 부분이 포함된 경우 사용하지 마십시오.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


WordProcessing에 대한 기본 로케일(언어)을 재정의하도록 설정할 수 있습니다.
문서이며, 생성 중에 적용됩니다. 지정되지 않은 경우
지정된 (기본값), MS Word(또는 다른 프로그램)는 감지(또는
선택) 문서 로케일을 자체 설정 또는 기타
요소에 따라 결정합니다.

*** ** * ** ***


이 옵션은 지정된 로케일을 전체 텍스트에 강제로 적용합니다
문서에. 문서에 다양한 부분이 포함된 경우 사용하지 마십시오
다양한 언어로 작성된 텍스트.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


WordProcessing 문서에 대한 로케일(언어)을 재정의하도록 설정할 수 있습니다.
RTL(오른쪽에서 왼쪽) 텍스트에 대해, 이는
생성 중. 지정되지 않은 경우 (기본값), MS Word(또는 다른
프로그램)는 자체 설정에 따라 문서 RTL 로케일을 감지(또는 선택)합니다
자체 설정 또는 기타 요소에 따라.

*** ** * ** ***


이 옵션은 지정된 로케일을 전체 RTL 텍스트에 강제로 적용합니다
문서에. 문서에 다양한 부분이 포함된 경우 사용하지 마십시오
다양한 언어로 작성된 텍스트.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


WordProcessing 문서에 대한 로케일(언어)을 재정의하도록 설정할 수 있습니다.
RTL(오른쪽에서 왼쪽) 텍스트에 대해, 이는
생성 중. 지정되지 않은 경우 (기본값), MS Word(또는 다른
프로그램)는 자체 설정에 따라 문서 RTL 로케일을 감지(또는 선택)합니다
자체 설정 또는 기타 요소에 따라.

*** ** * ** ***


이 옵션은 지정된 로케일을 전체 RTL 텍스트에 강제로 적용합니다
문서에. 문서에 다양한 부분이 포함된 경우 사용하지 마십시오
다양한 언어로 작성된 텍스트.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


WordProcessing 문서에 대한 로케일(언어)을 재정의할 수 있습니다.
동아시아 텍스트에 대해, 생성 중에 적용됩니다. 지정되지 않은 경우
지정되지 않은 경우 (기본값), MS Word(또는 다른 프로그램)는 감지합니다
(또는 선택) 문서 동아시아 로케일을 자체 설정에 따라
또는 기타 요소에 따라.

*** ** * ** ***


이 옵션은 지정된 로케일을 전체에 강제로 적용합니다
문서의 동아시아 텍스트에 적용합니다. 문서에 포함된 경우 사용하지 마십시오
다양한 언어로 작성된 텍스트의 다양한 부분이
언어들.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


WordProcessing 문서에 대한 로케일(언어)을 재정의할 수 있습니다.
동아시아 텍스트에 대해, 생성 중에 적용됩니다. 지정되지 않은 경우
지정되지 않은 경우 (기본값), MS Word(또는 다른 프로그램)는 감지합니다
(또는 선택) 문서 동아시아 로케일을 자체 설정에 따라
또는 기타 요소에 따라.

*** ** * ** ***


이 옵션은 지정된 로케일을 전체에 강제로 적용합니다
문서의 동아시아 텍스트에 적용합니다. 문서에 포함된 경우 사용하지 마십시오
다양한 언어로 작성된 텍스트의 다양한 부분이
언어들.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


문서 생성을 위해 HTML에서 메모리 최적화 메커니즘을 활성화합니다.
이는 메모리 사용량 감소를 대가로 성능을 저하시킵니다.
이 옵션을 true로 설정하면 메모리 사용량을 크게 줄일 수 있습니다
대용량 문서를 생성하는 동안 저장 시간이 느려지는 대가를 치르게 됩니다.
기본값은 false이며 (메모리 최적화가 더 나은
성능을 위해 비활성화됩니다).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


문서 생성을 위해 HTML에서 메모리 최적화 메커니즘을 활성화합니다.
이는 메모리 사용량 감소를 대가로 성능을 저하시킵니다.
이 옵션을 true로 설정하면 메모리 사용량을 크게 줄일 수 있습니다
대용량 문서를 생성하는 동안 저장 시간이 느려지는 대가를 치르게 됩니다.
기본값은 false이며 (메모리 최적화가 더 나은
성능을 위해 비활성화됩니다).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


문서 보호 옵션을 제어하고 적용할 수 있습니다.
어떤 형식이든 지원하는 WordProcessing 문서에 대해, 이는 문서
보호. 기본값은 NULL이며 - 문서 보호가 사용되지 않습니다.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


문서 보호 옵션을 제어하고 적용할 수 있습니다.
어떤 형식이든 지원하는 WordProcessing 문서에 대해, 이는 문서
보호. 기본값은 NULL이며 - 문서 보호가 사용되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


출력 WordProcessing에 글꼴 리소스를 포함시키는 역할을 합니다.
문서. 기본적으로 폰트를 포함하지 않습니다 (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


출력 WordProcessing에 글꼴 리소스를 포함시키는 역할을 합니다.
문서. 기본적으로 폰트를 포함하지 않습니다 (NotEmbed).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


이 인스턴스의 전체 복사본을 생성하고 반환합니다.
WordProcessingSaveOptions 클래스


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

