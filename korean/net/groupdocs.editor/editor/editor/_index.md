---
title: "Editor"
second_title: "GroupDocs.Editor .NET용 API 레퍼런스"
description: "Editorgroupdocs.editor/editor 클래스의 새 인스턴스를 초기화하고 지정된 형식을 기반으로 새로운 빈 문서를 생성합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

[`Editor`](../../editor) 클래스의 새 인스턴스를 초기화하고 지정된 형식을 기반으로 새 빈 문서를 생성합니다.

```csharp
public Editor(DocumentFormatBase format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 형식 | DocumentFormatBase | 생성될 문서의 파일 형식을 나타냅니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 예시

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // 편집기 인스턴스를 사용하여 문서를 편집하고 저장합니다.
}
```

### 참고

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

지정된 입력 문서(스트림)로 새 Editor 인스턴스를 초기화합니다.

```csharp
public Editor(Stream document)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 문서 | 스트림 | 문서 내용을 포함하는 스트림입니다. null이면 안 됩니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 예시

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // 편집기 인스턴스를 사용하여 문서를 편집하고 저장합니다.
    }
}
```

### 참고

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

지정된 입력 문서(스트림)와 로드 옵션으로 새로운 Editor 인스턴스를 초기화합니다.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 문서 | 스트림 | 문서 내용을 포함하는 스트림입니다. null이면 안 됩니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션입니다. null일 수 있습니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 문서 스트림이 null인 경우 발생합니다. |
| ArgumentException | 문서 스트림이 유효하지 않은 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 예시

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // 편집기 인스턴스를 사용하여 문서를 편집하고 저장합니다.
    }
}
```

### 참고

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

지정된 입력 문서(전체 파일 경로)와 로드 옵션으로 새로운 Editor 인스턴스를 초기화합니다.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | 문자열 | 파일의 전체 경로입니다. null이거나 비어 있거나 공백만 포함해서는 안 됩니다. 유효한 경로여야 하며 파일이 존재해야 합니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션입니다. null일 수 있습니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 파일 경로가 유효하지 않은 경우 발생합니다. |
| FileNotFoundException | 파일이 존재하지 않을 때 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 예시

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // 편집기 인스턴스를 사용하여 문서를 편집하고 저장합니다.
}
```

### 참고

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

지정된 입력 문서(전체 파일 경로)와 Editor 설정으로 새로운 Editor 인스턴스를 초기화합니다

```csharp
public Editor(string filePath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | 문자열 | 파일의 전체 경로입니다. NULL이면 안 됩니다. 유효한 경로여야 하며 파일이 존재해야 합니다. |

### 참고

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
