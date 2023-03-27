---
title: WorksheetNumber
second_title: .NET API 참조용 GroupDocs.Editor
description: 새 단일 워크시트 스프레드시트를 만드는 대신 기존 스프레드시트의 복사본에 편집된 워크시트를 삽입할 수 있습니다기본 동작. WorksheetNumber는 편집기 클래스에 로드된 스프레드시트에 있는 워크시트의 1부터 시작하는 번호입니다. 0기본값이면 편집된 단일 워크시트로 새 스프레드시트가 생성됩니다. 0보다 크거나 작으면 Editor 클래스에 로드된 유효한 스프레드시트가 있고 편집된 워크시트는 다음과 같이 표시됩니다. 입력 EditableDocument 인스턴스가 이 스프레드시트에 삽입됩니다.
type: docs
weight: 50
url: /ko/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

새 단일 워크시트 스프레드시트를 만드는 대신 기존 스프레드시트의 복사본에 편집된 워크시트를 삽입할 수 있습니다(기본 동작). WorksheetNumber는 편집기 클래스에 로드된 스프레드시트에 있는 워크시트의 1부터 시작하는 번호입니다. 0(기본값)이면 편집된 단일 워크시트로 새 스프레드시트가 생성됩니다. 0보다 크거나 작으면 Editor 클래스에 로드된 유효한 스프레드시트가 있고 편집된 워크시트는 다음과 같이 표시됩니다. 입력 EditableDocument 인스턴스가 이 스프레드시트에 삽입됩니다.

```csharp
public int WorksheetNumber { get; set; }
```

### 비고

워크시트 번호정수 속성은 기본 상태(예약값 '0')가 아닌 경우 워크시트 번호를 나타내므로 0이 아닌 1부터 시작하며 최대값은 프레젠테이션에 있는 모든 기존 슬라이드의 양입니다. 그러나 지정된 값이 모든 슬라이드의 양보다 큰 경우 GroupDocs.Editor는 마지막 워크시트를 표시하도록 조정합니다. 음수 값도 허용되며 끝에서부터 워크시트를 계산합니다. 예를 들어 "-1"은 스프레드시트의 마지막 워크시트를 의미하고 "-2"는 마지막 워크시트를 의미합니다. 양수 값과 마찬가지로 음수 워크시트 번호가 주어진 스프레드시트의 총 워크시트 수를 초과하면 다음과 같이 조정됩니다. 첫 번째 워크시트. [`InsertAsNewWorksheet`](../insertasnewworksheet) 부울 속성은 이것과 밀접하게 결합되어 있습니다.

### 예

지정된 스프레드시트에는 5개의 워크시트가 있습니다. WorksheetNumber = 0; — 지정된 스프레드시트를 무시하고 새 스프레드시트를 만들고 편집된 워크시트를 그 안에 넣습니다. WorksheetNumber = 1; — 첫 번째 워크시트를 edit WorksheetNumber = 2로 교체합니다. — 두 번째 워크시트를 edit WorksheetNumber = 5로 대체합니다. — 마지막(5번째) 워크시트를 edit WorksheetNumber = 6으로 대체합니다. — 마지막(5번째) 워크시트를 편집된 것으로 바꿉니다. 6은 5보다 크기 때문에 Adjustable WorksheetNumber = -1입니다. — "-1"은 "마지막 기존"을 의미하므로 마지막(5번째) 워크시트를 편집된 것으로 바꿉니다. WorksheetNumber = -2; — 네 번째 워크시트를 edited WorksheetNumber = -3으로 대체합니다. — 3번째 워크시트를 edit WorksheetNumber = -4로 대체합니다. — 두 번째 워크시트를 edit WorksheetNumber = -5로 대체합니다. — 첫 번째 워크시트를edited WorksheetNumber = -6으로 대체합니다. — 첫 번째 워크시트를 편집된 것으로 바꿉니다. "-6"이 5보다 커서 Adjustable 이기 때문입니다.

### 또한보십시오

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* 네임스페이스 [GroupDocs.Editor.Options](../../spreadsheetsaveoptions)
* 집회 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->