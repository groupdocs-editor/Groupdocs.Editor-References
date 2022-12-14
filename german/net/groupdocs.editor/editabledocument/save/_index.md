---
title: Save
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Speichert dieses HTMLDokument in der Datei im angegebenen Pfad in der das HTMLMarkup gespeichert wird und im zugehörigen Ordner mit Ressourcen.
type: docs
weight: 160
url: /de/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save}

Speichert dieses HTML-Dokument in der Datei im angegebenen Pfad, in der das HTML-Markup gespeichert wird, und im zugehörigen Ordner mit Ressourcen.

```csharp
public void Save(string htmlFilePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlFilePath | String | Vollständiger Pfad zur Datei, in der das HTML-Markup gespeichert wird. Datei wird erstellt oder überschrieben, falls vorhanden. Begleitender Ressourcenordner wird in demselben Ordner erstellt, in dem die HTML-Datei vorhanden ist. |

### Siehe auch

* class [EditableDocument](../../editabledocument)
* namensraum [GroupDocs.Editor](../../editabledocument)
* Montage [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_1}

Speichert dieses HTML-Dokument in der Datei im angegebenen Pfad, in der das HTML-Markup gespeichert wird, und im zugehörigen Ordner mit den Ressourcen , der sich im angegebenen Pfad befindet.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlFilePath | String | Vollständiger Pfad zur Datei, in der das HTML-Markup gespeichert wird. Kann nicht NULL oder leer sein. Datei wird erstellt oder überschrieben, falls vorhanden. |
| resourcesFolderPath | String | Vollständiger Pfad zum zugehörigen Ordner, in dem alle zugehörigen Ressourcen gespeichert werden. Wenn NULL oder leer, wird der Ordner automatisch im selben Verzeichnis erstellt, in dem sich die *.html-Datei befindet. Wenn angegeben und nicht vorhanden, wird erstellt. |

### Siehe auch

* class [EditableDocument](../../editabledocument)
* namensraum [GroupDocs.Editor](../../editabledocument)
* Montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
