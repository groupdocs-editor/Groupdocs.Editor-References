---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor .NET용 API 레퍼런스"
description: "모든 WordProcessing 형식을 캡슐화합니다. 다음 파일 유형이 포함됩니다."
type: docs
weight: 150
url: /ko/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

모든 워드 프로세싱 형식을 캡슐화합니다. 다음 파일 유형을 포함합니다:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Word Processing 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | 문서 형식의 파일 확장자를 가져옵니다. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | 문서 형식이 속한 형식 패밀리를 가져옵니다. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | 형식 패밀리의 고유 식별자를 가져옵니다. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | 문서 형식의 MIME 유형을 가져옵니다. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | 형식 패밀리의 이름을 가져옵니다. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | 모든 [`WordProcessingFormats`](../wordprocessingformats)의 열거 가능한 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | 지정된 파일 확장자를 가진 지정된 유형의 인스턴스를 [`WordProcessingFormats`](../wordprocessingformats)에서 검색합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | 이 인스턴스가 지정된 [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 확인합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | 이 인스턴스가 지정된 [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) 인스턴스와 같은지 확인합니다. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | 이 인스턴스가 지정된 [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스와 같은지 확인합니다. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 현재 객체에 대한 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 현재 객체를 나타내는 문자열을 반환합니다. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | 파일 확장자를 나타내는 문자열을 [`WordProcessingFormats`](../wordprocessingformats) 객체로 변환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 바이너리 파일 형식 (DOC)은 Microsoft Word 또는 기타 워드 프로세싱 프로그램에서 생성된 문서를 바이너리 파일 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML 매크로 사용 가능 문서 (DOCM) 파일은 매크로 실행 기능이 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML 매크로 없음 문서 (DOCX)는 Microsoft Word 문서에 널리 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 템플릿 (DOT)은 추가 DOC 또는 DOCX 파일 생성을 위한 사전 서식 설정을 갖춘 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML 매크로 사용 가능 템플릿 (DOTM)은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML 매크로 없음 템플릿 (DOTX)은 추가 DOCX 파일 생성을 위한 사전 서식 설정을 갖춘 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML은 ZIP 패키지 대신 평면 XML 파일에 저장됩니다. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format 텍스트 문서 (ODT) 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format 텍스트 문서 템플릿 (OTT)은 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF)은 애플리케이션 내에서 사용하기 위해 서식이 지정된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML 형식 — WordProcessingML 또는 WordML (.XML). |

### 참고

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
