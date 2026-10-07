---
title: "Editor"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Initialise une nouvelle instance de la classe Editorgroupdocs.editor/editor et crée un nouveau document vide basé sur le format spécifié."
type: docs
weight: 10
url: /fr/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Initialise une nouvelle instance de la classe [`Editor`](../../editor) et crée un nouveau document vide basé sur le format spécifié.

```csharp
public Editor(DocumentFormatBase format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| format | DocumentFormatBase | Représente le format de fichier du document qui sera créé. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exemples

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Utilisez l’instance de l’éditeur pour modifier et enregistrer des documents
}
```

### Voir aussi

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de flux).

```csharp
public Editor(Stream document)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Flux qui contient le contenu du document. Ne doit pas être nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exemples

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Utilisez l’instance de l’éditeur pour modifier et enregistrer des documents
    }
}
```

### Voir aussi

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de flux) avec ses options de chargement.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Flux qui contient le contenu du document. Ne doit pas être nul. |
| loadOptions | ILoadOptions | Options de chargement du document. Peut être nul. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque le flux du document est nul. |
| ArgumentException | Lancée lorsque le flux du document est invalide. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exemples

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Utilisez l’instance de l’éditeur pour modifier et enregistrer des documents
    }
}
```

### Voir aussi

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de chemin de fichier complet) avec ses options de chargement.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin complet vers le fichier. Ne doit pas être nul, vide ou ne contenir que des espaces. Doit être valide et le fichier doit exister. |
| loadOptions | ILoadOptions | Options de chargement du document. Peut être nul. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque le chemin du fichier est invalide. |
| FileNotFoundException | Lancée lorsque le fichier n'existe pas. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Exemples

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Utilisez l’instance de l’éditeur pour modifier et enregistrer des documents
}
```

### Voir aussi

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Initialise une nouvelle instance d'Editor avec le document d'entrée spécifié (sous forme de chemin de fichier complet) et les paramètres d'Editor.

```csharp
public Editor(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin complet vers le fichier. Ne doit pas être NULL. Doit être valide et le fichier doit exister. |

### Voir aussi

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
