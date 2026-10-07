---
title: "GetEmbeddedHtml"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie tout le contenu de ce document HTML avec toutes les ressources associées sous la forme d'une chaîne unique où toutes les ressources sont intégrées dans le balisage HTML sous forme codée en base64."
type: docs
weight: 150
url: /fr/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

Renvoie l'intégralité du contenu de ce document HTML avec toutes les ressources associées sous forme d'une chaîne unique, où toutes les ressources sont intégrées dans le balisage HTML sous forme codée en base64.

```csharp
public string GetEmbeddedHtml()
```

### Valeur de retour

Chaîne, qui n'est jamais NULL ou vide

### Exceptions

| exception | condition |
| --- | --- |
| ObjectDisposedException | Cette instance d'EditableDocument a déjà été libérée |

### Remarques

Cette méthode convertit cet EditableDocument en HTML et le sérialise en une chaîne unique, où toutes les ressources sont intégrées à la chaîne avec le balisage HTML :

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
