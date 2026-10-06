---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Abstrakte Basisklasse für die Optionen aller Dokumente mit festem Layout wie PDF und XPS."
type: docs
weight: 16
url: /de/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Abstrakte Basisklasse für die Optionen aller Dokumente mit festem Layout wie PDF und XPS.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Liest oder setzt das Flag, das angibt, ob Bilder beim Konvertieren des Eingabedokuments mit festem Layout in das resultierende HTML übersprungen werden müssen. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Liest oder setzt das Flag, das angibt, ob Bilder beim Konvertieren des Eingabedokuments mit festem Layout in das resultierende HTML übersprungen werden müssen. |
|
|  | [getPages()](#getPages--) | Ermöglicht das Festlegen eines Seitenbereichs zum Verarbeiten. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Ermöglicht das Festlegen eines Seitenbereichs zum Verarbeiten. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Ermöglicht das Aktivieren (true) oder Deaktivieren (false) der Seitennummerierung im resultierenden HTML-Dokument. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ermöglicht das Aktivieren (true) oder Deaktivieren (false) der Seitennummerierung im resultierenden HTML-Dokument. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Liest oder setzt das Flag, das angibt, ob Bilder beim Konvertieren des Eingabedokuments mit festem Layout in das resultierende HTML übersprungen werden müssen. Standard ist false - Bilder werden beibehalten.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Liest oder setzt das Flag, das angibt, ob Bilder beim Konvertieren des Eingabedokuments mit festem Layout in das resultierende HTML übersprungen werden müssen. Standard ist false - Bilder werden beibehalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Ermöglicht das Festlegen eines Seitenbereichs zum Verarbeiten. Standardmäßig werden alle Seiten eines Dokuments mit festem Layout verarbeitet.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Ermöglicht das Festlegen eines Seitenbereichs zum Verarbeiten. Standardmäßig werden alle Seiten eines Dokuments mit festem Layout verarbeitet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Ermöglicht das Aktivieren (true) oder Deaktivieren (false) der Seitennummerierung im resultierenden HTML-Dokument. Standardmäßig ist sie deaktiviert (false).

<br />

*** ** * ** ***

Dokumente im Fixed‑Layout‑Format (insbesondere PDF und XPS) sind im Wesentlichen streng paginiert, ihr Inhalt hat ein festes Layout und ist auf Seiten aufgeteilt. Das resultierende editierbare HTML kann jedoch entweder in einer seitenlosen oder paginierten Ansicht dargestellt werden.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Ermöglicht das Aktivieren (true) oder Deaktivieren (false) der Seitennummerierung im resultierenden HTML-Dokument. Standardmäßig ist sie deaktiviert (false).

<br />

*** ** * ** ***

Dokumente im Fixed‑Layout‑Format (insbesondere PDF und XPS) sind im Wesentlichen streng paginiert, ihr Inhalt hat ein festes Layout und ist auf Seiten aufgeteilt. Das resultierende editierbare HTML kann jedoch entweder in einer seitenlosen oder paginierten Ansicht dargestellt werden.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

