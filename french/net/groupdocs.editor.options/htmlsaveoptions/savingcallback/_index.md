---
title: "SavingCallback"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Interface qui doit être implémentée par l'utilisateur final pour enregistrer toutes les ressources HTML externes. Cette propriété ne doit pas être null sinon GroupDocs.Editor lèvera une exception lors de l’enregistrement de EditableDocumentgroupdocs.editor/editabledocument au format HTML."
type: docs
weight: 50
url: /fr/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

Interface qui doit être implémentée par l'utilisateur final pour enregistrer toutes les ressources HTML externes. Cette propriété **doit** ne pas être `null`, sinon GroupDocs.Editor lèvera une exception lors de l’enregistrement de [`EditableDocument`](../../../groupdocs.editor/editabledocument) au format HTML.

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### Remarques

Si la valeur de la propriété [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) est définie sur `true`, toutes les feuilles de style seront intégrées au balisage HTML et ne seront donc pas transmises à ce rappel d’enregistrement.

### Voir aussi

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
