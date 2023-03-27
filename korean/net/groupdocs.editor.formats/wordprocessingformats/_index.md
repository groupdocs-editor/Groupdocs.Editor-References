---
title: WordProcessingFormats
second_title: .NET API 참조용 GroupDocs.Editor
description: 모든 WordProcessing 형식을 캡슐화합니다. 다음 파일 형식을 포함합니다. Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . 워드 프로세싱 형식에 대해 자세히 알아보기여기https//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /ko/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

모든 WordProcessing 형식을 캡슐화합니다. 다음 파일 형식을 포함합니다. [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . 워드 프로세싱 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | 이 WordProcessing 형식의 확장자(선행 점 문자 없음)를 소문자로 반환합니다 |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | 이 format 에 대한 MIME 코드를 반환합니다. |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | 이 워드프로세싱 format 의 공식적인 전체 이름을 반환합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | 인스턴스 반환[`WordProcessingFormats`](../wordprocessingformats) 지정된 파일 이름 확장자와 연결된 구조이거나 확장자를 제대로 구문 분석할 수 없는 경우 예외가 발생합니다 |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | 이 인스턴스가 지정된 다른 IDocumentFormat instance 와 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | 이 인스턴스가 지정된 다른 개체, 즉 상자형 WordProcessingFormats 와 같은지 여부를 결정합니다. |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | 이 인스턴스가 지정된 다른 WordProcessingFormats instance 와 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | 이 instance 에 대해 변경할 수 없는 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | '이름' property 와 같은 이 특정 형식의 이름을 반환합니다. |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | equal 에서 두 개의 지정된 WordProcessingFormats 인스턴스를 확인합니다. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | 지정된 WordProcessingFormats instance 의 기본 필드에서 바이트 값을 반환합니다. (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | inequality 에서 주어진 두 개의 WordProcessingFormats 인스턴스를 확인합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 이진 파일 형식(DOC)은 Microsoft Word에서 생성된 문서 또는 기타 워드 프로세싱 문서를 이진 파일 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML 매크로 사용 문서(DOCM) 파일은 매크로 실행 기능이 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML DOCX(Macro-Free Document)는 잘 알려진 Microsoft Word 문서 형식입니다. 2007년부터 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식의 구조는 일반 바이너리에서 XML 및 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 템플릿은 추가 DOC 또는 DOCX 파일 생성을 위해 미리 형식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML DOTM(Macro-Enabled Template)은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML DOTX(Macro-Free Template)는 추가 DOCX 파일 생성을 위한 사전 형식 설정을 포함하기 위해 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | ZIP 패키지 대신 플랫 XML 파일에 저장된 Office Open XML WordprocessingML package |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | ODT(Open Document Format Text Document) 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 응용 프로그램으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | OTT(Open Document Format) 텍스트 문서 템플릿(OTT)은 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | RTF(서식 있는 텍스트 형식)는 응용 프로그램 내에서 사용하기 위해 형식이 지정된 텍스트 및 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML 형식 — WordProcessingML 또는 WordML(.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | 기존의 모든 WordProcessing 형식에 대해 열거 가능한 가능성을 제공하는 내부 클래스를 반환합니다. |

## 다른 멤버들

| 이름 | 설명 |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | WordProcessingFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |

### 비고

MIME 코드는 지정된 리소스에서 가져옵니다.

### 또한보십시오

* interface [IDocumentFormat](../idocumentformat)
* 네임스페이스 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
