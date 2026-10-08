---
title: "Save"
second_title: "GroupDocs.Editor .NET용 API 레퍼런스"
description: "지정된 편집된 문서를 EditableDocumentgroupdocs.editor/editabledocument 인스턴스로 표현하여 지정된 형식의 결과 문서로 변환하고, 해당 내용을 지정된 스트림에 저장합니다."
type: docs
weight: 80
url: /ko/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

지정된 편집된 문서를 '[`EditableDocument`](../../editabledocument)' 인스턴스로 표현하여 지정된 형식의 결과 문서로 변환하고, 해당 내용을 지정된 스트림에 저장합니다.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML‑editor에서 편집된 입력 문서의 버전으로, '[`EditableDocument`](../../editabledocument)' 클래스의 인스턴스로 저장되어 있으며, 특정 형식의 출력 문서로 변환되어야 합니다. null이거나 해제되지 않아야 합니다. |
| outputDocument | 스트림 | 출력 스트림으로, 결과 문서의 내용이 기록됩니다. null이 아니어야 하며, 폐기되지 않아야 하고, 쓰기 기능을 지원해야 합니다. |
| saveOptions | ISaveOptions | 문서 저장 옵션으로, 결과 문서의 형식을 정의하고 일반 및 형식별 저장 옵션을 포함합니다. null이 아니어야 합니다. |

### 비고

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### 참고

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

지정된 편집 문서를 '[`EditableDocument`](../../editabledocument)' 인스턴스로 표현된 것을 지정된 형식의 결과 문서로 변환하고, 지정된 파일 경로에 파일로 내용을 저장합니다.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML‑editor에서 편집된 입력 문서의 버전으로, '[`EditableDocument`](../../editabledocument)' 클래스의 인스턴스로 저장되어 있으며, 특정 형식의 출력 문서로 변환되어야 합니다. null이거나 해제되지 않아야 합니다. |
| filePath | 문자열 | 출력 문서가 저장될 파일의 경로입니다. 동일한 이름의 파일이 존재하면 완전히 덮어쓰게 됩니다. 경로 문자열은 null이 아니어야 하고, 비어 있거나 공백만 포함해서도 안 됩니다. |
| saveOptions | ISaveOptions | 문서 저장 옵션으로, 결과 문서의 형식을 정의하고 일반 및 형식별 저장 옵션을 포함합니다. null이 아니어야 합니다. |

### 비고

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### 참고

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

지정된 편집 문서를 '[`EditableDocument`](../../editabledocument)' 인스턴스로 표현된 것을 파일 이름 확장자에서 결정된 형식의 결과 문서로 변환하고, 지정된 파일 경로에 파일로 내용을 저장합니다.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML‑editor에서 편집된 입력 문서의 버전으로, '[`EditableDocument`](../../editabledocument)' 클래스의 인스턴스로 저장되어 있으며, 특정 형식의 출력 문서로 변환되어야 합니다. null이거나 해제되지 않아야 합니다. |
| filePath | 문자열 | 출력 문서가 저장될 파일의 경로입니다. 동일한 이름의 파일이 존재하면 완전히 덮어쓰게 됩니다. 경로 문자열은 null이 아니어야 하고, 비어 있거나 공백만 포함해서도 안 됩니다. 기본 저장 옵션과 출력 형식이 이 파일 이름에서 결정되므로, 유효한 확장자를 가져야 합니다. |

### 참고

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

수정 후 원본 문서를 (예: [`FormFieldManager`](../formfieldmanager)) 지정된 형식의 결과 문서로 변환하고, 제공된 스트림에 내용을 저장합니다.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| outputDocument | 스트림 | 출력 문서가 저장될 스트림입니다. 이 스트림은 쓰기 가능하고 문서 내용의 시작 위치에 있어야 합니다. null이 아니어야 합니다. |
| saveOptions | WordProcessingSaveOptions | 결과 문서의 형식과 일반 및 형식별 저장 옵션을 정의하는 문서 저장 옵션입니다. null이 아니어야 합니다. |

### 반환 값

저장된 문서 내용을 포함하는 스트림입니다.

### 비고

*outputDocument* 또는 *saveOptions*가 null인 경우 ArgumentNullException이 발생합니다. 저장할 문서가 없으면 ArgumentNullException이 발생합니다.

*outputDocument* 또는 *saveOptions*가 null이거나 저장할 문서가 없을 때 발생합니다.**Learn more:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### 참고

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

현재 문서 내용을 지정된 출력 스트림에 저장합니다.

```csharp
public Stream Save(Stream outputDocument)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| outputDocument | 스트림 | 문서 내용이 저장될 스트림입니다. 이는 null일 수 없습니다. |

### 반환 값

저장된 문서 내용을 가진 스트림입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *outputDocument*가 null이거나 문서 내용이 없을 때 발생합니다. |

### 비고

이 메서드는 내부 문서 표현에서 제공된 출력 스트림으로 내용을 복사합니다. 저장 작업 후 스트림의 원래 위치가 유지됩니다.

### 참고

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
