---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt Metadaten eines E‑Mail‑Dokuments in einem beliebigen unterstützten E‑Mail‑Format dar"
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Stellt Metadaten eines E‑Mail‑Dokuments in einem beliebigen unterstützten E‑Mail‑Format dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt das Format dieses E-Mail-Dokuments zurück |
|
|  | [getPageCount()](#getPageCount--) | Gibt immer 1 zurück, weil E-Mail-Dokumente keine seitenbasierte Ansicht haben |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes dieses E-Mail-Dokuments zurück |
|
|  | [isEncrypted()](#isEncrypted--) | Da E-Mail-Dokumente nicht mit einem Passwort verschlüsselt werden können, gibt diese Eigenschaft immer 'false' zurück |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Bestimmt, ob diese Instanz gleich der anderen angegebenen EmailDocumentInfo-Instanz ist |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Gibt das Format dieses E-Mail-Dokuments zurück


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gibt immer 1 zurück, weil E-Mail-Dokumente keine seitenbasierte Ansicht haben


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Gibt die Größe in Bytes dieses E-Mail-Dokuments zurück


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Da E-Mail-Dokumente nicht mit einem Passwort verschlüsselt werden können, gibt diese Eigenschaft immer 'false' zurück


**Returns:**
boolesch
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Bestimmt, ob diese Instanz gleich der anderen angegebenen EmailDocumentInfo-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Andere EmailDocumentInfo-Instanz, die auf Gleichheit mit dieser geprüft werden sollte |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

