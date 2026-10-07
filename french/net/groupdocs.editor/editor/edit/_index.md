---
title: "Edit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Ouvre un document préalablement chargé pour le modifier en utilisant des options spécifiques au format en générant et en renvoyant une instance de la classe EditableDocumentgroupdocs.editor/editabledocument qui, à son tour, contient des méthodes pour produire du balisage HTML et les ressources associées."
type: docs
weight: 60
url: /fr/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

Ouvre un document préalablement chargé pour le modifier en utilisant des options spécifiques au format en générant et en renvoyant une instance de la classe '[`EditableDocument`](../../editabledocument)', qui, à son tour, contient des méthodes pour produire du balisage HTML et les ressources associées.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| editOptions | IEditOptions | Options de document spécifiques au format, qui permettent d’ajuster le processus de conversion. Peut être NULL — dans ce cas GroupDocs.Editor détecte le format du document précédemment chargé et applique les options par défaut pour ce format. Ne doit pas entrer en conflit avec les options de chargement précédemment appliquées. |

### Valeur de retour

Instance de la classe '[`EditableDocument`](../../editabledocument)', qui encapsule le document d’entrée complet avec toutes ses ressources au format intermédiaire. Cette méthode, si elle se termine avec succès, ne renvoie jamais NULL.

### Remarques

Lorsque le document original d’entrée est chargé dans l’instance 'Editor' via le constructeur, cette méthode permet d’ouvrir le document pour le modifier en le convertissant au format intermédiaire, qui est encapsulé dans une instance de la classe 'EditableDocument'. '[`EditableDocument`](../../editabledocument)', renvoyé par cette méthode, contient toutes les méthodes et propriétés nécessaires pour produire le balisage HTML et les ressources correspondantes (comme les images, les polices et les feuilles de style) dans toutes les configurations requises pour les transmettre ensuite à n’importe quel éditeur HTML WYSIWYG. Cette surcharge obtient des options d’édition, qui sont spécifiques aux familles de formats. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Voir aussi

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

Ouvre un document précédemment chargé pour le modifier en utilisant les options par défaut en générant et en renvoyant une instance de la classe '[`EditableDocument`](../../editabledocument)', qui, à son tour, contient des méthodes pour produire le balisage HTML et les ressources associées.

```csharp
public EditableDocument Edit()
```

### Valeur de retour

Instance de la classe '[`EditableDocument`](../../editabledocument)', qui encapsule le document d’entrée complet avec toutes ses ressources au format intermédiaire. Cette méthode, si elle se termine avec succès, ne renvoie jamais NULL.

### Remarques

Lorsque le document original d’entrée est chargé dans l’instance 'Editor' via le constructeur, cette méthode permet d’ouvrir le document pour le modifier en le convertissant au format intermédiaire, qui est encapsulé dans une instance de la classe '[`EditableDocument`](../../editabledocument)'. '[`EditableDocument`](../../editabledocument)', renvoyé par cette méthode, contient toutes les méthodes et propriétés nécessaires pour produire le balisage HTML et les ressources correspondantes (comme les images, les polices et les feuilles de style) dans toutes les configurations requises pour les transmettre ensuite à n’importe quel éditeur HTML WYSIWYG. Cette surcharge applique les options d’édition, qui sont les options par défaut pour le format auquel appartient le document d’entrée. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Voir aussi

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
