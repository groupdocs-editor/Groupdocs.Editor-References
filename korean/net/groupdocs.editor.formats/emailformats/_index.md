---
title: "EmailFormats"
second_title: "GroupDocs.Editor .NET용 API 레퍼런스"
description: "모든 이메일 형식을 캡슐화합니다. 다음 파일 유형을 포함합니다 Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /ko/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

모든 이메일 형식을 캡슐화합니다. 다음 파일 유형을 포함합니다: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | 문서 형식의 파일 확장자를 가져옵니다. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | 문서 형식이 속한 형식 패밀리를 가져옵니다. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | 형식 패밀리의 고유 식별자를 가져옵니다. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | 문서 형식의 MIME 유형을 가져옵니다. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | 형식 패밀리의 이름을 가져옵니다. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | 모든 [`EmailFormats`](../emailformats)의 열거 가능한 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | 지정된 파일 확장자를 가진 지정된 유형 [`EmailFormats`](../emailformats)의 인스턴스를 검색합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | 이 인스턴스가 지정된 [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 확인합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | 이 인스턴스가 지정된 [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) 인스턴스와 같은지 확인합니다. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | 이 인스턴스가 지정된 [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스와 같은지 확인합니다. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 현재 객체에 대한 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 현재 객체를 나타내는 문자열을 반환합니다. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | 파일 확장자를 나타내는 문자열을 [`EmailFormats`](../emailformats) 객체로 변환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/eml/)를 클릭하십시오. |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX 파일 형식은 Apple에서 구현 및 개발되었습니다. Apple Mail 애플리케이션은 이메일을 내보내기 위해 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/emlx/)를 클릭하십시오. |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML 형식의 이메일. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification(iCalendar)은 캘린더 이벤트와 일정 교환 및 배포를 위한 인터넷 표준(RFC 2445)입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/ics/)를 클릭하십시오. |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox 파일 형식은 전자 메일 메시지 컬렉션을 위한 컨테이너를 나타내는 일반적인 용어입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/mbox/)를 클릭하십시오. |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML은 "MIME encapsulation of aggregate HTML documents"의 약어입니다. |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용되는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/msg/)를 클릭하십시오. |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | .oft 확장자를 가진 파일은 Microsoft Outlook을 사용하여 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/oft/)를 클릭하십시오. |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Offline Storage Table(OST) 파일은 Microsoft Outlook을 사용하여 Exchange Server에 등록할 때 로컬 컴퓨터에서 오프라인 모드로 사용자의 사서함 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/ost/)를 클릭하십시오. |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | .pst 확장자를 가진 파일은 다양한 사용자 정보를 저장하는 Outlook 개인 저장 파일(또는 Personal Storage Table)입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/email/pst/)를 클릭하십시오. |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF)은 Microsoft의 독점 형식으로, Messaging Application Programming Interface (MAPI)를 기반으로 이메일 첨부 파일을 캡슐화합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) 또는 vCard는 연락처 정보를 저장하는 디지털 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/email/vcf/). |

### 비고

이메일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/email/).

### 참고

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
