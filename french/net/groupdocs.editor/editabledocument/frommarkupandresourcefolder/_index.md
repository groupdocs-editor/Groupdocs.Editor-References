---
title: "FromMarkupAndResourceFolder"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Fabrique statique qui crée une instance d'EditableDocument à partir d'un balisage HTML spécifié et des ressources situées dans le dossier indiqué par le chemin complet."
type: docs
weight: 30
url: /fr/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

Fabrique statique qui crée une instance de EditableDocument à partir d'un balisage HTML spécifié et à partir des ressources situées dans le dossier indiqué par le chemin complet

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newHtmlContent | String | Chaîne contenant le balisage HTML brut qui doit être analysé. Ne peut pas être NULL, vide ou invalide. |
| resourceFolderPath | String | Chemin obligatoire vers le dossier contenant les ressources. Toutes les feuilles de style situées dans ce dossier seront utilisées. Ne peut pas être NULL ou une chaîne vide, et ce dossier doit exister. |

### Valeur de retour

Nouvelle instance non nulle d'EditableDocument

### Remarques

Cette fabrique statique est utile lorsque le contenu d'un document HTML est présenté sous forme de chaîne, mais que toutes les ressources se trouvent dans un dossier, et que les liens vers ces ressources dans le balisage HTML sont souvent invalides ou absents. Lors de l'appel de cette méthode, elle parcourt le dossier spécifié et applique automatiquement toutes les feuilles de style trouvées au document. Cette méthode est très utile lors de l'obtention de contenu provenant de différents éditeurs HTML, qui suppriment généralement les métadonnées du document, etc.

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
