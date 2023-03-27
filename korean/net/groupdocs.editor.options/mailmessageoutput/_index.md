---
title: MailMessageOutput
second_title: .NET API 참조용 GroupDocs.Editor
description: 출력 처리 로 전달되어야 하는 메일 메시지 부분을 제어합니다.
type: docs
weight: 950
url: /ko/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

출력 처리 로 전달되어야 하는 메일 메시지 부분을 제어합니다.

```csharp
[Flags]
public enum MailMessageOutput : ushort
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 이메일 메시지 부분이 처리되지 않습니다 |
| Body | `1` | 메일 message 의 본문 처리 |
| Subject | `2` | 메일 message 의 프로세스 제목 |
| Date | `4` | 메시지가 배달된 날짜 및 시간 처리 |
| To | `8` | 메일 message 의 모든 수신자를 처리합니다. |
| Cc | `10` | 메일 message 의 모든 참조 수신자를 처리합니다. |
| Bcc | `20` | 메일 message 의 모든 BCC 수신자를 처리합니다. |
| From | `40` | 메일 message 의 발신자를 처리합니다. |
| Attachments | `80` | 메일 message 의 모든 첨부 파일 처리 |
| Metadata | `100` | 기타 모든 기술 메타데이터 처리(민감도, 우선 순위, 인코딩, MIME, X-Mailer 등) |
| Common | `7B` | 공통 출력 - 모든 기본 메타데이터가 있는 본문 |
| All | `1FF` | 전체 출력 - 모든 metadata 가 포함된 본문 |

### 또한보십시오

* 네임스페이스 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->