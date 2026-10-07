---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "XPS XML Paper Specifications 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다"
type: docs
weight: 54
url: /ko/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

XPS(XML Paper Specifications) 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

<br />

*** ** * ** ***

XPS 파일은 Microsoft에서 만든 XML Paper Specifications를 기반으로 하는 페이지 레이아웃 파일을 나타냅니다. EMF 파일 형식을 대체하기 위해 개발되었으며 PDF 파일 형식과 유사하지만 문서의 레이아웃, 외관 및 인쇄 정보를 XML로 사용합니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | 원본 문서에서 사용되는 글꼴 리소스를 결과 XPS 문서에 포함시키는 역할을 합니다. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML에서 문서를 생성하는 동안 메모리 사용량을 감소시키는 대가로 성능이 저하되는 메모리 최적화 메커니즘을 활성화합니다. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


원본 문서에서 사용되는 글꼴 리소스를 결과 XPS 문서에 포함시키는 역할을 합니다.
기본적으로 글꼴을 포함하지 않습니다 (NotEmbed).


**Returns:**
바이트
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

