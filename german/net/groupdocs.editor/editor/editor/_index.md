---
title: Editor
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Initialisiert eine neue EditorInstanz mit dem angegebenen Eingabedokument als Stream
type: docs
weight: 10
url: /de/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream)

```csharp
public Editor(Func<Stream> document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Delegate, der einen Stream mit Dokumentinhalt zurückgeben sollte. Sollte nicht NULL sein. |

### Bemerkungen

**Erfahren Sie mehr**

* Mehr zu den von GroupDocs.Editor unterstützten Dateitypen: [Von GroupDocs.Editor unterstützte Dokumentformate](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Mehr über GroupDocs.Editor für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Siehe auch

* class [Editor](../../editor)
* namensraum [GroupDocs.Editor](../../editor)
* Montage [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream) mit seinen Ladeoptionen

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Delegate, der einen Stream mit Dokumentinhalt zurückgeben sollte. Sollte nicht NULL sein. |
| loadOptions | Func`1 | Delegat, der eine Dokumentladeoption zurückgeben sollte. Kann NULL sein und kann null zurückgeben - in diesem Fall wird der Dokumenttyp automatisch erkannt und Standardladeoptionen für diesen Typ werden angewendet. |

### Bemerkungen

**Erfahren Sie mehr**

* Mehr zu den von GroupDocs.Editor unterstützten Dateitypen: [Von GroupDocs.Editor unterstützte Dokumentformate](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Mehr über GroupDocs.Editor für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Weitere Informationen zum Öffnen und Bearbeiten von passwortgeschützten Dokumenten und Dokumenten aus verschiedenen Speichern: [Laden und bearbeiten Sie Dokumente mit GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namensraum [GroupDocs.Editor](../../editor)
* Montage [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad)

```csharp
public Editor(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Vollständiger Pfad zur Datei. Sollte nicht NULL sein. Sollte gültig sein und die Datei sollte vorhanden sein. |

### Bemerkungen

**Erfahren Sie mehr**

* Mehr zu den von GroupDocs.Editor unterstützten Dateitypen: [Von GroupDocs.Editor unterstützte Dokumentformate](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Mehr über GroupDocs.Editor für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Siehe auch

* class [Editor](../../editor)
* namensraum [GroupDocs.Editor](../../editor)
* Montage [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) mit seinen Ladeoptionen

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Vollständiger Pfad zur Datei. Sollte nicht NULL sein. Sollte gültig sein und die Datei sollte vorhanden sein. |
| loadOptions | Func`1 | Delegat, der eine Dokumentladeoption zurückgeben sollte. Kann NULL sein und kann null zurückgeben - in diesem Fall wird der Dokumenttyp automatisch erkannt und Standardladeoptionen für diesen Typ werden angewendet. |

### Bemerkungen

**Erfahren Sie mehr**

* Mehr zu den von GroupDocs.Editor unterstützten Dateitypen: [Von GroupDocs.Editor unterstützte Dokumentformate](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Mehr über GroupDocs.Editor für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Weitere Informationen zum Öffnen und Bearbeiten von passwortgeschützten Dokumenten und Dokumenten aus verschiedenen Speichern: [Laden und bearbeiten Sie Dokumente mit GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namensraum [GroupDocs.Editor](../../editor)
* Montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
