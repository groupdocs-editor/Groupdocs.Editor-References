---
title: GroupDocs.Editor.Formats
second_title: .NET API 참조용 GroupDocs.Editor
description: GroupDocs.Editor.Formats 네임스페이스는 지원되는 문서 형식을 설명하는 인터페이스와 클래스를 제공합니다.
type: docs
weight: 20
url: /ko/net/groupdocs.editor.formats/
---
GroupDocs.Editor.Formats 네임스페이스는 지원되는 문서 형식을 설명하는 인터페이스와 클래스를 제공합니다.

## 클래스

| 수업 | 설명 |
| --- | --- |
| [EBookFormats.AllEnumerable](./ebookformats.allenumerable) | EBookFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |
| [EmailFormats.AllEnumerable](./emailformats.allenumerable) | 전자 메일 type 에 대해 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |
| [FixedLayoutFormats.AllEnumerable](./fixedlayoutformats.allenumerable) | FixedLayoutFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |
| [PresentationFormats.AllEnumerable](./presentationformats.allenumerable) | PresentationFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |
| [SpreadsheetFormats.AllEnumerable](./spreadsheetformats.allenumerable) | SpreadsheetFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |
| [TextualFormats.AllEnumerable](./textualformats.allenumerable) | TextualFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |
| [WordProcessingFormats.AllEnumerable](./wordprocessingformats.allenumerable) | WordProcessingFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |
## 구조

| 구조 | 설명 |
| --- | --- |
| [EBookFormats](./ebookformats) | 모든 eBook 형식을 캡슐화합니다. 다음 파일 형식을 포함합니다. [`Mobi`](../groupdocs.editor.formats/ebookformats/mobi) , [`Epub`](../groupdocs.editor.formats/ebookformats/epub) , [`Azw3`](../groupdocs.editor.formats/ebookformats/azw3) |
| [EmailFormats](./emailformats) | 모든 이메일 형식을 캡슐화합니다. 다음 파일 형식을 포함합니다. [`Tnef`](../groupdocs.editor.formats/emailformats/tnef) , [`Eml`](../groupdocs.editor.formats/emailformats/eml) , [`Emlx`](../groupdocs.editor.formats/emailformats/emlx) , [`Msg`](../groupdocs.editor.formats/emailformats/msg) , [`Html`](../groupdocs.editor.formats/emailformats/html) , [`Mhtml`](../groupdocs.editor.formats/emailformats/mhtml) . |
| [FixedLayoutFormats](./fixedlayoutformats) | PDF 및 XPS를 포함하는 모든 고정 레이아웃("고정 페이지"라고도 함) 형식을 캡슐화합니다(래스터 이미지는 포함하지 않음) |
| [PresentationFormats](./presentationformats) | 모든 프레젠테이션 형식을 캡슐화합니다. 다음 형식을 포함합니다. [`Odp`](../groupdocs.editor.formats/presentationformats/odp) , [`Otp`](../groupdocs.editor.formats/presentationformats/otp) , [`Pot`](../groupdocs.editor.formats/presentationformats/pot) , [`Potm`](../groupdocs.editor.formats/presentationformats/potm) , [`Potx`](../groupdocs.editor.formats/presentationformats/potx) , [`Pps`](../groupdocs.editor.formats/presentationformats/pps) , [`Ppsm`](../groupdocs.editor.formats/presentationformats/ppsm) , [`Ppsx`](../groupdocs.editor.formats/presentationformats/ppsx) , [`Ppt`](../groupdocs.editor.formats/presentationformats/ppt) , [`Ppt95`](../groupdocs.editor.formats/presentationformats/ppt95) , [`Pptm`](../groupdocs.editor.formats/presentationformats/pptm) , [`Pptx`](../groupdocs.editor.formats/presentationformats/pptx). 프레젠테이션 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation) . |
| [SpreadsheetFormats](./spreadsheetformats) | 통합 문서를 저장할 수 있는 모든 이진, XML 및 텍스트 스프레드시트 형식(CSV, TSV, 세미콜론 구분 등과 같은 구분 기호가 있는 모든 텍스트 구분 기호 기반 형식 제외)을 캡슐화합니다. 다음 형식을 포함합니다. [`Dif`](../groupdocs.editor.formats/spreadsheetformats/dif) , [`Fods`](../groupdocs.editor.formats/spreadsheetformats/fods) , [`Ods`](../groupdocs.editor.formats/spreadsheetformats/ods) , [`Sxc`](../groupdocs.editor.formats/spreadsheetformats/sxc) , [`Xlam`](../groupdocs.editor.formats/spreadsheetformats/xlam) , [`Xls`](../groupdocs.editor.formats/spreadsheetformats/xls) , [`Xlsb`](../groupdocs.editor.formats/spreadsheetformats/xlsb) , [`Xlsm`](../groupdocs.editor.formats/spreadsheetformats/xlsm) , [`Xlsx`](../groupdocs.editor.formats/spreadsheetformats/xlsx) , [`Xlt`](../groupdocs.editor.formats/spreadsheetformats/xlt) , [`Xltm`](../groupdocs.editor.formats/spreadsheetformats/xltm) , [`Xltx`](../groupdocs.editor.formats/spreadsheetformats/xltx) . 스프레드시트 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet) . |
| [TextualFormats](./textualformats) | 마크업(XML, HTML) 및 기타를 포함하여 모든 텍스트(텍스트 기반) 형식을 캡슐화합니다. 다음 형식을 포함합니다. [`Html`](../groupdocs.editor.formats/textualformats/html) , [`Txt`](../groupdocs.editor.formats/textualformats/txt) , [`Xml`](../groupdocs.editor.formats/textualformats/xml) . [`Md`](../groupdocs.editor.formats/textualformats/md) , [`Json`](../groupdocs.editor.formats/textualformats/json) . |
| [WordProcessingFormats](./wordprocessingformats) | 모든 WordProcessing 형식을 캡슐화합니다. 다음 파일 형식을 포함합니다. [`Doc`](../groupdocs.editor.formats/wordprocessingformats/doc) , [`Docm`](../groupdocs.editor.formats/wordprocessingformats/docm) , [`Docx`](../groupdocs.editor.formats/wordprocessingformats/docx) , [`Dot`](../groupdocs.editor.formats/wordprocessingformats/dot) , [`Dotm`](../groupdocs.editor.formats/wordprocessingformats/dotm) , [`Dotx`](../groupdocs.editor.formats/wordprocessingformats/dotx) , [`FlatOpc`](../groupdocs.editor.formats/wordprocessingformats/flatopc) , [`Odt`](../groupdocs.editor.formats/wordprocessingformats/odt) , [`Ott`](../groupdocs.editor.formats/wordprocessingformats/ott) , [`Rtf`](../groupdocs.editor.formats/wordprocessingformats/rtf) , [`WordML`](../groupdocs.editor.formats/wordprocessingformats/wordml) . 워드 프로세싱 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing) . |
## 인터페이스

| 상호 작용 | 설명 |
| --- | --- |
| [IDocumentFormat](./idocumentformat) | 모든 지원 문서 형식에 대한 루트 인터페이스 |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
