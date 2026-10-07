---
title: "LocaleBi"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de définir un remplacement de la langue locale pour le document WordProcessing destiné au texte RTL (de droite à gauche) qui sera appliqué lors de sa création. Si aucune valeur n'est spécifiée, la valeur par défaut de MS Word ou d'un autre programme détectera ou choisira la locale RTL du document selon ses propres paramètres ou d'autres facteurs."
type: docs
weight: 50
url: /fr/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

Permet de définir un remplacement de la locale (langue) pour le texte RTL (de droite à gauche) du document WordProcessing, qui sera appliqué lors de sa création. Lorsqu'elle n'est pas spécifiée (valeur par défaut), MS Word (ou un autre programme) détectera (ou choisira) la locale RTL du document en fonction de ses propres paramètres ou d'autres facteurs.

```csharp
public CultureInfo LocaleBi { get; set; }
```

### Remarques

Cette option applique de force la locale spécifiée à l'ensemble du texte RTL du document. Ne l'utilisez pas si le document contient différentes parties de texte écrites dans différentes langues.

### Voir aussi

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
