---
title: "LocaleId"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Obtient ou définit l'ID de paramètre régional du champ de formulaire qui représente la culture ou les paramètres régionaux associés au champ de formulaire."
type: docs
weight: 30
url: /fr/net/groupdocs.editor.words.fieldmanagement/dropdownformfield/localeid/
---
## DropDownFormField.LocaleId property

Obtient ou définit l'ID de paramètre régional du champ de formulaire, qui représente la culture ou les paramètres régionaux associés au champ de formulaire.

```csharp
public int LocaleId { get; set; }
```

### Remarques

La propriété LocaleId spécifie un identifiant de paramètre régional (LCID) qui correspond à une culture ou une région particulière.

### Exemples

L'exemple suivant montre comment définir la propriété LocaleId :

```csharp
Set the LocaleId to represent the English (United States) culture
dropDownField.LocaleId = new CultureInfo("en-US").LCID;
```

### Voir aussi

* class [DropDownFormField](../../dropdownformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
