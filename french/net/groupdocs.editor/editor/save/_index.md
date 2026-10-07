---
title: "Save"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit le document édité spécifié, représenté comme instance de EditableDocumentgroupdocs.editor/editabledocument, en le document résultant du format spécifié et enregistre son contenu dans le flux spécifié"
type: docs
weight: 80
url: /fr/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Convertit le document édité spécifié, représenté comme instance de '[`EditableDocument`](../../editabledocument)', en le document résultant du format spécifié et enregistre son contenu dans le flux spécifié

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputDocument | EditableDocument | Version du document d’entrée, qui a été éditée dans l’éditeur HTML WYSIWYG et est stockée comme instance de la classe '[`EditableDocument`](../../editabledocument)', qui doit être convertie en document de sortie d’un format spécifique. Ne doit pas être nul ou libéré. |
| outputDocument | Stream | Flux de sortie, dans lequel le contenu du document résultant sera enregistré. Ne doit pas être nul, libéré, et doit prendre en charge l’écriture. |
| saveOptions | ISaveOptions | Options d’enregistrement du document, qui définissent le format du document résultant, ainsi que les options d’enregistrement générales et spécifiques au format. Ne doit pas être nul. |

### Remarques

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Voir aussi

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Convertit le document édité spécifié, représenté comme instance de '[`EditableDocument`](../../editabledocument)', en le document résultant du format spécifié et enregistre son contenu dans un fichier au chemin de fichier spécifié

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputDocument | EditableDocument | Version du document d’entrée, qui a été éditée dans l’éditeur HTML WYSIWYG et est stockée comme instance de la classe '[`EditableDocument`](../../editabledocument)', qui doit être convertie en document de sortie d’un format spécifique. Ne doit pas être nul ou libéré. |
| filePath | String | Chemin du fichier dans lequel le document de sortie sera enregistré. Si un fichier du même nom existe, il sera complètement réécrit. La chaîne de chemin ne doit pas être nulle, vide ou ne contenir que des espaces. |
| saveOptions | ISaveOptions | Options d’enregistrement du document, qui définissent le format du document résultant, ainsi que les options d’enregistrement générales et spécifiques au format. Ne doit pas être nul. |

### Remarques

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Voir aussi

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Convertit le document édité spécifié, représenté comme instance de '[`EditableDocument`](../../editabledocument)', en le document résultant au format déterminé à partir de l'extension du nom de fichier, et enregistre son contenu dans un fichier au chemin spécifié.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputDocument | EditableDocument | Version du document d’entrée, qui a été éditée dans l’éditeur HTML WYSIWYG et est stockée comme instance de la classe '[`EditableDocument`](../../editabledocument)', qui doit être convertie en document de sortie d’un format spécifique. Ne doit pas être nul ou libéré. |
| filePath | String | Chemin du fichier dans lequel le document de sortie sera enregistré. Si un fichier portant le même nom existe, il sera complètement réécrit. La chaîne du chemin ne doit pas être nulle, vide ou ne contenir que des espaces. Étant donné que les options d’enregistrement par défaut et le format de sortie sont déterminés à partir de ce nom de fichier, il doit posséder une extension valide. |

### Voir aussi

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Convertit le document original après modification (par exemple, [`FormFieldManager`](../formfieldmanager)), en le document résultant du format spécifié et enregistre son contenu dans le flux fourni.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputDocument | Stream | Le flux dans lequel le document de sortie sera enregistré. Ce flux doit être accessible en écriture et positionné au début du contenu du document. Ne doit pas être nul. |
| saveOptions | WordProcessingSaveOptions | Options d’enregistrement du document qui définissent le format du document résultant, ainsi que les options d’enregistrement générales et spécifiques au format. Ne doit pas être nul. |

### Valeur de retour

Le flux contenant le contenu du document enregistré.

### Remarques

Si *outputDocument* ou *saveOptions* est nul, une ArgumentNullException sera levée. Si le document à enregistrer est manquant, une ArgumentNullException sera levée.

Levée lorsque *outputDocument* ou *saveOptions* est nul, ou lorsque le document à enregistrer est manquant.**En savoir plus:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Voir aussi

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Enregistre le contenu du document actuel dans le flux de sortie spécifié.

```csharp
public Stream Save(Stream outputDocument)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputDocument | Stream | Le flux dans lequel le contenu du document sera enregistré. Cela ne peut pas être nul. |

### Valeur de retour

Le flux contenant le contenu du document enregistré.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *outputDocument* est nul ou si le contenu du document est manquant. |

### Remarques

Cette méthode copie le contenu de la représentation interne du document vers le flux de sortie fourni. La position originale du flux est préservée après l’opération d’enregistrement.

### Voir aussi

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
