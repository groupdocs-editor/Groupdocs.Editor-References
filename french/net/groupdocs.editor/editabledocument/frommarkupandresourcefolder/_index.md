---
title: FromMarkupAndResourceFolder
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Usine statique qui crée une instance de EditableDocument à partir dun balisage HTML spécifié et de ressources situées dans le dossier spécifié par le chemin complet
type: docs
weight: 30
url: /fr/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

Usine statique, qui crée une instance de EditableDocument à partir d'un balisage HTML spécifié et de ressources, situées dans le dossier, spécifié par le chemin complet

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newHtmlContent | String | Chaîne, qui contient un balisage HTML brut, qui doit être analysé. Ne peut pas être NULL, vide ou invalide. |
| resourceFolderPath | String | Chemin obligatoire vers le dossier avec les ressources. Toutes les feuilles de style, qui se trouvent dans ce dossier, seront utilisées. Ne peut pas être NULL ou une chaîne vide, et ce dossier doit exister. |

### Return_Value

Nouvelle instance non nulle de EditableDocument

### Remarques

Cette fabrique statique est utile lorsque le contenu du document HTML est présenté sous forme de chaîne, mais que toutes les ressources sont situées dans un dossier et que, souvent, les liens vers ces ressources dans le balisage HTML sont invalides et absents. Lors de l'appel de cette méthode, il analyse le dossier spécifié et applique automatiquement toutes les feuilles de style trouvées au document. Cette méthode est très utile lors de l'obtention de contenu à partir de différents éditeurs HTML, qui coupent généralement les métadonnées du document, etc.

### Voir également

* class [EditableDocument](../../editabledocument)
* espace de noms [GroupDocs.Editor](../../editabledocument)
* Assemblée [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
