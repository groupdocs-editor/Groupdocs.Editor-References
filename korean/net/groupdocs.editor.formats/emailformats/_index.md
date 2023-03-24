---
title: EmailFormats
second_title: .NET API 참조용 GroupDocs.Editor
description: 모든 이메일 형식을 캡슐화합니다. 다음 파일 형식을 포함합니다. Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /ko/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

모든 이메일 형식을 캡슐화합니다. 다음 파일 형식을 포함합니다. [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | 구현 형식에서 형식 파일 확장명을 반환해야 합니다(선행 점 문자 없이). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | type 구현에서 주어진 format 에 대한 MIME 코드를 반환해야 합니다. |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | 구현 형식에서 전체 형식 형식 name 를 반환해야 합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | 인스턴스 반환[`EmailFormats`](../emailformats) 지정된 파일 이름 확장자와 연결된 구조이거나 확장자를 제대로 구문 분석할 수 없는 경우 예외가 발생합니다 |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | 이 인스턴스가 다른 지정된 이메일 instance 와 동일한지 여부를 결정합니다. |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | 이 인스턴스가 지정된 다른 IDocumentFormat instance 와 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | 이 인스턴스가 다른 지정된 개체, 즉 boxed Email 와 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | 이 instance 에 대해 변경할 수 없는 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | 이 format 의 형식 이름을 반환합니다. |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | 동등성에서 주어진 두 개의 이메일 인스턴스를 확인합니다 |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | inequality 에서 주어진 두 개의 이메일 인스턴스를 확인합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML 파일 형식은 Outlook 및 기타 관련 응용 프로그램을 사용하여 저장된 전자 메일 메시지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX 파일 형식은 Apple에서 구현하고 개발합니다. Apple Mail 애플리케이션은 이메일 내보내기에 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML 형식의 이메일. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | iCalendar(Internet Calendaring and Scheduling Core Object Specification)는 일정 이벤트 및 일정을 교환 및 배포하기 위한 인터넷 표준(RFC 2445)입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox 파일 형식은 전자 메일 메시지 수집을 위한 컨테이너를 나타내는 일반적인 용어입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, "집계 HTML 문서의 MIME 캡슐화" 의 약자 |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG는 Microsoft Outlook 및 Exchange에서 전자 메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용하는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | 확장자가 .oft인 파일은 Microsoft Outlook을 사용하여 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | OST(Offline Storage Table) 파일은 Microsoft Outlook을 사용하여 Exchange Server에 등록할 때 로컬 시스템에서 오프라인 모드로 사용자의 사서함 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | 확장자가 .pst인 파일은 다양한 사용자 정보를 저장하는 Outlook 개인 저장소 파일(개인 저장소 테이블이라고도 함)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | TNEF(Transport Neutral Encapsulation Format)는 MAPI(Messaging Application Programming Interface)를 기반으로 이메일 첨부 파일을 캡슐화하기 위한 Microsoft 소유의 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF(Virtual Card Format) 또는 vCard는 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | 기존의 모든 이메일 형식에 대해 열거 가능한 가능성을 제공하는 내부 클래스를 반환합니다 |

## 다른 멤버들

| 이름 | 설명 |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | 전자 메일 type 에 대해 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |

### 비고

이메일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/email/) .

### 또한보십시오

* interface [IDocumentFormat](../idocumentformat)
* 네임스페이스 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
