---
title: EpubSaveOptions
second_title: .NET API 참조용 GroupDocs.Editor
description: IDPF EPUB 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다국제 디지털 출판 포럼에서 만든 전자책의 공개 표준
type: docs
weight: 870
url: /ko/net/groupdocs.editor.options/epubsaveoptions/
---
## EpubSaveOptions class

IDPF EPUB 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다(국제 디지털 출판 포럼에서 만든 전자책의 공개 표준)

```csharp
public sealed class EpubSaveOptions : ISaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EpubSaveOptions](epubsaveoptions)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/epubsaveoptions/exportdocumentproperties) { get; set; } | 내장 및 사용자 지정 문서 속성을 IDPF EPUB 형식으로 내보낼지 여부를 지정합니다. 기본값은 다음과 같습니다.`거짓` . |
| [SplitHeadingLevel](../../groupdocs.editor.options/epubsaveoptions/splitheadinglevel) { get; set; } | ePub 파일을 분할할 제목의 최대 수준을 지정합니다. 기본값은`2` . 로 설정`0` 분할을 비활성화하므로 e-Book의 모든 콘텐츠가 ePub 내부의 단일 패키지로 통합됩니다. |

### 또한보십시오

* interface [ISaveOptions](../isaveoptions)
* 네임스페이스 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->