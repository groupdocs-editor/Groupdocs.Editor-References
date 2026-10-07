---
title: "FromFile"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Fabrique statique qui crée une instance d'EditableDocument à partir d'un fichier HTML spécifié par le chemin du fichier .html lui-même et d'un dossier contenant les ressources liées"
type: docs
weight: 10
url: /fr/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Fabrique statique qui crée une instance de EditableDocument à partir d'un fichier HTML, spécifié par le chemin du fichier *.html lui‑-même et d'un dossier contenant les ressources liées

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlFilePath | String | Chaîne contenant le chemin complet du fichier HTML. Ne peut pas être nul, doit être un chemin de fichier valide, et le fichier lui-même doit exister. |
| resourceFolderPath | String | Chemin optionnel vers le dossier contenant les ressources HTML. Si NULL, invalide ou si ce dossier n'existe pas, l'éditeur essaiera de trouver ce dossier lui-même en analysant le balisage HTML |

### Valeur de retour

Nouvelle instance non nulle d'EditableDocument

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Le chemin du fichier HTML et/ou le chemin du dossier de ressources est invalide |
| FileNotFoundException | Le fichier HTML spécifié est introuvable |

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
