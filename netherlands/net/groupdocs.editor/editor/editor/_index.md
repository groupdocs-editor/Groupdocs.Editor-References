---
title: Editor
second_title: GroupDocs.Editor voor .NET API-referentie
description: Initialiseert nieuwe Editorinstantie met opgegeven invoerdocument als een stream
type: docs
weight: 10
url: /nl/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een stream)

```csharp
public Editor(Func<Stream> document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | Delegate, dat zou een stream met documentinhoud moeten retourneren. Mag niet NULL zijn. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Editor: [Documentformaten ondersteund door GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Meer over GroupDocs.Editor voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Zie ook

* class [Editor](../../editor)
* naamruimte [GroupDocs.Editor](../../editor)
* montage [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een stream) met zijn laadopties

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | Delegate, dat zou een stream met documentinhoud moeten retourneren. Mag niet NULL zijn. |
| loadOptions | Func`1 | Delegate, dat zou een documentlaadopties moeten retourneren. Kan NULL zijn en kan null - retourneren, in dat geval wordt het documenttype automatisch gedetecteerd en worden de standaard laadopties voor dat type toegepast. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Editor: [Documentformaten ondersteund door GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Meer over GroupDocs.Editor voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Meer over het openen en bewerken van met een wachtwoord beveiligde documenten en documenten uit verschillende opslagplaatsen: [Laad en bewerk documenten met GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Zie ook

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* naamruimte [GroupDocs.Editor](../../editor)
* montage [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een volledig bestandspad)

```csharp
public Editor(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Volledig pad naar het bestand. Mag niet NULL zijn. Moet geldig zijn en het bestand moet bestaan. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Editor: [Documentformaten ondersteund door GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Meer over GroupDocs.Editor voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Zie ook

* class [Editor](../../editor)
* naamruimte [GroupDocs.Editor](../../editor)
* montage [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Initialiseert nieuwe Editor-instantie met opgegeven invoerdocument (als een volledig bestandspad) met zijn laadopties

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Volledig pad naar het bestand. Mag niet NULL zijn. Moet geldig zijn en het bestand moet bestaan. |
| loadOptions | Func`1 | Delegate, dat zou een documentlaadopties moeten retourneren. Kan NULL zijn en kan null - retourneren, in dat geval wordt het documenttype automatisch gedetecteerd en worden de standaard laadopties voor dat type toegepast. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Editor: [Documentformaten ondersteund door GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Meer over GroupDocs.Editor voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Meer over het openen en bewerken van met een wachtwoord beveiligde documenten en documenten uit verschillende opslagplaatsen: [Laad en bewerk documenten met GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Zie ook

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* naamruimte [GroupDocs.Editor](../../editor)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
