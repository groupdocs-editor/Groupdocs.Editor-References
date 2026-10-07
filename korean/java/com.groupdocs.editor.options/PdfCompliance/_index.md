---
title: "PdfCompliance"
second_title: "GroupDocs.Editor for Java API 참조"
description: "PDF 표준 준수 수준을 지정합니다."
type: docs
weight: 28
url: /ko/java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

PDF 표준 준수 수준을 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Pdf17](#Pdf17) | PDF 1.7 (ISO 32000-1) 표준 |
|
|  | [Pdf20](#Pdf20) | PDF 2.0 (ISO 32000-2) 표준 |
|
|  | [PdfA1a](#PdfA1a) | PDF/A-1a 표준. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | PDF/A-2a (ISO 19005-2) 표준. |
|
|  | [PdfA2u](#PdfA2u) | PDF/A-2u (ISO 19005-2) 표준. |
|
|  | [PdfUa1](#PdfUa1) | PDF/UA-1 (ISO 14289-1) 표준. |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7 (ISO 32000-1) 표준


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0 (ISO 32000-2) 표준


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a 표준. 이 수준은 PDF/A-1b의 모든 요구 사항을 포함하며 추가로 문서 구조가 포함되어야 합니다.
("tagged"라고도 함), 문서 내용이 검색되고 재활용될 수 있도록 보장하는 것을 목표로 합니다.

<br />

*** ** * ** ***

문서 구조를 내보내면 메모리 사용량이 크게 증가한다는 점에 유의하십시오, 특히 큰 문서의 경우.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b는 문서의 시각적 모습을 신뢰성 있게 재현하는 것을 목표로 합니다.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a (ISO 19005-2) 표준. 이 수준은 PDF/A-2u의 모든 요구 사항을 포함하며 추가로 문서 구조가 포함되어야 합니다 ("tagged"라고도 함), 문서 내용이 검색되고 재활용될 수 있도록 보장하는 것을 목표로 합니다.

<br />

*** ** * ** ***

문서 구조를 내보내면 메모리 사용량이 크게 증가한다는 점에 유의하십시오, 특히 큰 문서의 경우.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u (ISO 19005-2) 표준. PDF/A-2u는 문서의 정적 시각적 모습을 시간이 지나도 보존하는 것을 목표로 하며, 문서를 생성, 저장 또는 렌더링하는 데 사용되는 도구와 시스템에 독립적입니다. 또한 문서에 포함된 모든 텍스트는 유니코드 코드 포인트 시퀀스로 신뢰성 있게 추출될 수 있습니다.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1 (ISO 14289-1) 표준. PDF/UA의 주요 목적은 파일을 접근 가능하도록 PDF 형식으로 전자 문서를 표현하는 방법을 정의하는 것입니다.


