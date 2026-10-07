---
title: "HtmlSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour enregistrer l'instance EditableDocument../groupdocs.editor/editabledocument au format HTML"
type: docs
weight: 900
url: /fr/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

Permet de spécifier des options personnalisées pour enregistrer l'instance [`EditableDocument`](../../groupdocs.editor/editabledocument) au format HTML

```csharp
public sealed class HtmlSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | Contrôle le délimiteur à utiliser autour des valeurs d'attribut dans les éléments HTML : guillemet simple (valeur par défaut) ou guillemet double |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | Contrôle où stocker les feuilles de style CSS : en tant que ressources externes (`false`), ou les incorporer dans le balisage HTML, à l'intérieur de l'élément STYLE dans la section HTML-&gt;HEAD (`true`) |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | Contrôle la façon dont les noms de balises HTML apparaissent dans le balisage HTML : tout en minuscules (valeur par défaut), tout en majuscules, ou première lettre en majuscule |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | Interface qui doit être implémentée par l'utilisateur final pour enregistrer toutes les ressources HTML externes. Cette propriété **must** ne doit pas être `null`, sinon GroupDocs.Editor lèvera une exception lors de l'enregistrement de [`EditableDocument`](../../groupdocs.editor/editabledocument) au format HTML. |

### Voir aussi

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
