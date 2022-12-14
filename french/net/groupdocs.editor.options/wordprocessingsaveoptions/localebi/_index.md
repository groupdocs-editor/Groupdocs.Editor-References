---
title: LocaleBi
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Permet de définir des paramètres régionaux de remplacement langue pour le document WordProcessing pour le texte RTL de droite à gauche qui sera appliqué lors de sa création. Lorsque nest pas spécifié valeur par défaut MS Word ou autre programme détectera ou choisira le document RTL locale en fonction de ses propres paramètres ou dautres facteurs.
type: docs
weight: 50
url: /fr/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

Permet de définir des paramètres régionaux de remplacement (langue) pour le document WordProcessing pour le texte RTL (de droite à gauche), qui sera appliqué lors de sa création. Lorsque n'est pas spécifié (valeur par défaut), MS Word (ou autre programme) détectera (ou choisira) le document RTL locale en fonction de ses propres paramètres ou d'autres facteurs.

```csharp
public CultureInfo LocaleBi { get; set; }
```

### Remarques

Cette option applique de force les paramètres régionaux spécifiés à l'ensemble du texte RTL dans le document. Ne l'utilisez pas si le document contient différentes parties de texte, qui sont écrites dans différentes langues.

### Voir également

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* espace de noms [GroupDocs.Editor.Options](../../wordprocessingsaveoptions)
* Assemblée [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
