---
title: "FromMarkup"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Fabrique statique qui crée une instance de EditableDocumentgroupdocs.editor/editabledocument à partir du balisage HTML spécifié."
type: docs
weight: 20
url: /fr/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

Fabrique statique qui crée une instance de [`EditableDocument`](../../editabledocument) à partir du balisage HTML spécifié.

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newHtmlContent | String | Chaîne contenant le balisage HTML brut qui doit être analysé. Ne peut pas être NULL, vide ou invalide. |

### Valeur de retour

Nouvelle instance non nulle d'EditableDocument

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La chaîne contenant le balisage HTML brut d'entrée ne peut pas être null ou vide. |

### Remarques

Cette méthode statique est utile pour créer l'instance de [`EditableDocument`](../../editabledocument) à partir d'un balisage HTML sous forme d'une seule chaîne, où toutes les ressources sont intégrées avec un encodage base64.

### Voir aussi

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

Fabrique statique qui crée une instance de EditableDocument à partir du balisage HTML spécifié et d'un ensemble de ressources liées correspondantes

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newHtmlContent | String | Chaîne contenant le balisage HTML brut qui doit être analysé. Ne peut pas être NULL, vide ou invalide. |
| resources | IEnumerable`1 | Collection de toutes les ressources (images, feuilles de style, polices), utilisées dans le document HTML, spécifiées dans le paramètre *newHtmlContent*. Peut être absent (NULL ou collection vide). |

### Valeur de retour

Nouvelle instance non nulle d'EditableDocument

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La chaîne contenant le balisage HTML brut d'entrée ne peut pas être null ou vide. |

### Voir aussi

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
