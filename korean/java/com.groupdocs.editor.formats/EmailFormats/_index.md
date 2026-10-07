---
title: "EmailFormats"
second_title: "GroupDocs.Editor for Java API 참조"
description: "모든 이메일 형식을 캡슐화합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

모든 이메일 형식을 캡슐화합니다. 다음 파일 유형을 포함합니다:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

이메일 형식에 대해 자세히 알아보려면 [here](../https://docs.fileformat.com/email/)에서 확인하세요.

<br />


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format(TNEF)은 Messaging Application Programming Interface(MAPI)를 기반으로 이메일 첨부 파일을 캡슐화하기 위한 Microsoft 독점 형식입니다. |
|
|  | [Eml](#Eml) | EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다. |
|
|  | [Emlx](#Emlx) | EMLX 파일 형식은 Apple에 의해 구현 및 개발되었습니다. |
|
|  | [Msg](#Msg) | MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용되는 파일 형식입니다. |
|
|  | [Html](#Html) | HTML 형식의 이메일. |
|
|  | [Mhtml](#Mhtml) | MHTML은 "MIME encapsulation of aggregate HTML documents"의 약어입니다. |
|
|  | [Ics](#Ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar)은 캘린더 이벤트와 일정 교환 및 배포를 위한 인터넷 표준(RFC 2445)입니다. |
|
|  | [Vcf](#Vcf) | VCF(가상 카드 형식) 또는 vCard는 연락처 정보를 저장하는 디지털 파일 형식입니다. |
|
|  | [Pst](#Pst) | .pst 확장자를 가진 파일은 Outlook 개인 저장 파일(또는 Personal Storage Table)로, 다양한 사용자 정보를 저장합니다. |
|
|  | [Mbox](#Mbox) | MBox 파일 형식은 전자 메일 메시지 모음을 위한 컨테이너를 나타내는 일반적인 용어입니다. |
|
|  | [Oft](#Oft) | .oft 확장자를 가진 파일은 Microsoft Outlook을 사용하여 만든 템플릿 파일입니다. |
|
|  | [Ost](#Ost) | Offline Storage Table (OST) 파일은 Microsoft Outlook을 사용하여 Exchange Server에 등록할 때 로컬 컴퓨터에서 오프라인 모드로 사용자의 메일함 데이터를 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 [EmailFormats](../../com.groupdocs.editor.formats/emailformats)의 열거 가능한 컬렉션을 가져옵니다. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 지정된 파일 확장자를 가진 지정된 유형 [EmailFormats](../../com.groupdocs.editor.formats/emailformats)의 인스턴스를 검색합니다. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 파일 확장자를 나타내는 문자열을 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 객체로 변환합니다. |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format(TNEF)은 Messaging Application Programming Interface(MAPI)를 기반으로 이메일 첨부 파일을 캡슐화하기 위한 Microsoft 독점 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


EMLX 파일 형식은 Apple에 의해 구현 및 개발되었습니다. Apple Mail 애플리케이션은 이메일을 내보내는 데 EMLX 파일 형식을 사용합니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용되는 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML 형식의 이메일.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML은 "MIME encapsulation of aggregate HTML documents"의 약어입니다.


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Internet Calendaring and Scheduling Core Object Specification (iCalendar)은 캘린더 이벤트와 일정 교환 및 배포를 위한 인터넷 표준(RFC 2445)입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF(가상 카드 형식) 또는 vCard는 연락처 정보를 저장하는 디지털 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


.pst 확장자를 가진 파일은 Outlook 개인 저장 파일(또는 Personal Storage Table)로, 다양한 사용자 정보를 저장합니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox 파일 형식은 전자 메일 메시지 모음을 위한 컨테이너를 나타내는 일반적인 용어입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


.oft 확장자를 가진 파일은 Microsoft Outlook을 사용하여 만든 템플릿 파일입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Offline Storage Table (OST) 파일은 Microsoft Outlook을 사용하여 Exchange Server에 등록할 때 로컬 컴퓨터에서 오프라인 모드로 사용자의 메일함 데이터를 나타냅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


모든 [EmailFormats](../../com.groupdocs.editor.formats/emailformats)의 열거 가능한 컬렉션을 가져옵니다.
값: 모든 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 인스턴스를 포함하는 IEnumerable{EmailFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


지정된 파일 확장자를 가진 지정된 유형 [EmailFormats](../../com.groupdocs.editor.formats/emailformats)의 인스턴스를 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 문서 형식의 파일 확장자입니다. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


파일 확장자를 나타내는 문자열을 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 변환할 파일 확장자입니다. 확장자에 마침표가 여러 개 포함된 경우, 마지막 마침표 이후의 부분이 사용됩니다. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

