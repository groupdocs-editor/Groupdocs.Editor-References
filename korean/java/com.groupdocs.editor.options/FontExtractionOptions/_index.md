---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "글꼴 추출 옵션은 어떤 글꼴을 추출하고 어디에서 추출할지 제어합니다"
type: docs
weight: 18
url: /ko/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

글꼴 추출 옵션은 어떤 글꼴을 추출하고 어디에서 추출할지 제어합니다
어디서

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NotExtract](#NotExtract) | 문서에서도, 그 외에서도 어떤 글꼴 리소스도 추출하지 않습니다 |
시스템.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | 입력 Word에 포함된 모든 글꼴 리소스를 추출합니다 |
문서, 커스텀이든 시스템이든 관계없이.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | 커스텀인 포함된 글꼴 리소스만 추출합니다 (시스템은 |
시스템)
|
|  | [ExtractAll](#ExtractAll) | 입력 WordProcessing에서 사용되는 모든 글꼴을 추출하려고 시도합니다 |
문서, 시스템 글꼴을 포함합니다.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


문서에서도, 그 외에서도 어떤 글꼴 리소스도 추출하지 않습니다
시스템. 기본값.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


입력 Word에 포함된 모든 글꼴 리소스를 추출합니다
문서, 커스텀이든 시스템이든 관계없이.


*** ** * ** ***

Converter는 입력 WordProcessing 문서에 포함된 모든 100% 글꼴 리소스를 찾아 추출하지만, 해당 글꼴이 시스템인지 커스텀인지 판단하지 않으며; Windows Registry나 시스템 폴더를 전혀 건드리지 않습니다.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


커스텀인 포함된 글꼴 리소스만 추출합니다 (시스템은
시스템)


*** ** * ** ***

Converter는 모든 포함된 글꼴 리소스를 찾아 추출한 다음, 이 중 어떤 글꼴이 시스템이고 어떤 글꼴이 아닌지 판단하려고 시도합니다. 이를 위해 Converter는 Windows Registry와 시스템 폴더를 사용하여 모든 시스템 글꼴 목록을 얻은 뒤, 해당 목록을 포함된 글꼴 집합과 비교합니다. 결과적으로 시스템에서 찾을 수 없는 포함된 글꼴의 일부만 반환됩니다.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


입력 WordProcessing에서 사용되는 모든 글꼴을 추출하려고 시도합니다
문서, 시스템 글꼴을 포함합니다.


*** ** * ** ***

Converter는 입력 WordProcessing 문서를 분석하여 사용된 모든 글꼴을 찾습니다. 이러한 글꼴이 모두 입력 문서에 포함되어 있으면, Converter는 이를 추출하여 반환합니다. 반대로 포함된 글꼴 컬렉션이 문서에서 사용된 모든 글꼴을 포괄하지 않거나 비어 있는 경우, Converter는 Windows Registry와 시스템 폴더를 사용하여 시스템에서 해당 글꼴 리소스를 추출하려고 시도합니다.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
