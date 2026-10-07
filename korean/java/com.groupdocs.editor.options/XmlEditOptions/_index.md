---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "XML(eXtensible Markup Language) 문서를 로드하고 HTML로 변환하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 51
url: /ko/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

XML(eXtensible Markup Language) 로드를 위한 사용자 지정 옵션을 지정할 수 있습니다.
문서를 HTML로 변환합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | 텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다 |
열기.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다 |
열기.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | 손상된 XML 구조를 복구하는 메커니즘을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | 손상된 XML 구조를 복구하는 메커니즘을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | URI 인식 알고리즘을 활성화하도록 허용합니다 |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | URI 인식 알고리즘을 활성화하도록 허용합니다 |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | 속성에서 이메일 주소 인식 알고리즘을 활성화하도록 허용합니다 |
값
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | 속성에서 이메일 주소 인식 알고리즘을 활성화하도록 허용합니다 |
값
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | inner-tag 내의 뒤쪽 공백을 잘라내는 것을 활성화하도록 허용합니다 |
텍스트.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | inner-tag 내의 뒤쪽 공백을 잘라내는 것을 활성화하도록 허용합니다 |
텍스트.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | 속성 값에 대한 인용 부호 유형(단일 또는 이중 인용 부호)을 지정하도록 허용합니다. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 속성 값에 대한 인용 부호 유형(단일 또는 이중 인용 부호)을 지정하도록 허용합니다. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | HTML로 표시될 때 XML 구조에 적용될 XML 하이라이팅을 조정하도록 허용합니다. |
|
|  | [getFormatOptions()](#getFormatOptions--) | HTML로 표시될 때 XML 구조에 적용될 XML 포맷팅을 조정하도록 허용합니다. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다
열기. 기본값은 null이며 \\u2014 내부 문서 인코딩이 적용됩니다.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다
열기. 기본값은 null이며 \\u2014 내부 문서 인코딩이 적용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


손상된 XML 구조를 복구하는 메커니즘을 활성화하거나 비활성화할 수 있습니다.
기본값은 비활성화됩니다 (false).

*** ** * ** ***


기본적으로 올바른 형식의 유효한 XML 문서만
허용됩니다. 이 옵션을 활성화하면 GroupDocs.Editor가 수정을 시도합니다
가능한 경우 손상된 XML 구조를 복구합니다.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


손상된 XML 구조를 복구하는 메커니즘을 활성화하거나 비활성화할 수 있습니다.
기본값은 비활성화됩니다 (false).

*** ** * ** ***


기본적으로 올바른 형식의 유효한 XML 문서만
허용됩니다. 이 옵션을 활성화하면 GroupDocs.Editor가 수정을 시도합니다
가능한 경우 손상된 XML 구조를 복구합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


URI 인식 알고리즘을 활성화하도록 허용합니다


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


URI 인식 알고리즘을 활성화하도록 허용합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


속성에서 이메일 주소 인식 알고리즘을 활성화하도록 허용합니다
값


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


속성에서 이메일 주소 인식 알고리즘을 활성화하도록 허용합니다
값


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


inner-tag 내의 뒤쪽 공백을 잘라내는 것을 활성화하도록 허용합니다
텍스트. 기본값은 비활성화됩니다 (false) \\u2014 뒤쪽 공백은
보존됩니다.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


inner-tag 내의 뒤쪽 공백을 잘라내는 것을 활성화하도록 허용합니다
텍스트. 기본값은 비활성화됩니다 (false) \\u2014 뒤쪽 공백은
보존됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


속성 값에 대한 인용 부호 유형(단일 또는 이중 인용 부호)을 지정하도록 허용합니다. 이중 인용 부호가 기본값입니다.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


속성 값에 대한 인용 부호 유형(단일 또는 이중 인용 부호)을 지정하도록 허용합니다. 이중 인용 부호가 기본값입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


HTML로 표시될 때 XML 구조에 적용될 XML 하이라이팅을 조정하도록 허용합니다. 기본 하이라이팅이 사용되며 조정 가능합니다. null일 수 없습니다.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


HTML로 표시될 때 XML 구조에 적용될 XML 포맷팅을 조정하도록 허용합니다. 기본 포맷팅이 사용되며 조정 가능합니다. null일 수 없습니다.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
