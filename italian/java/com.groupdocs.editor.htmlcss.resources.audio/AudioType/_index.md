---
title: "AudioType"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta un formato audio supportabile"
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Rappresenta un tipo audio supportabile (formato)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Nome formale di questo formato audio |
|
|  | [getFileExtension()](#getFileExtension--) | Estensione del nome file (senza il carattere punto) per questo formato audio |
|
|  | [getMimeCode()](#getMimeCode--) | Codice MIME per questo formato audio |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Determina se questa istanza è uguale all'istanza "AudioType" specificata |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza è uguale all'oggetto non convertito specificato, che presumibilmente è un'altra istanza di "AudioType" |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Verifica se due valori "AudioType" sono uguali |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Verifica se due valori "AudioType" non sono uguali |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash, che è un numero costante per questo tipo di valore specifico |
|
|  | [getUndefined()](#getUndefined--) | Valore speciale, che indica un formato audio non definito, sconosciuto o non supportato |
|
|  | [getMp3()](#getMp3--) | Rappresenta un formato audio MPEG-1 Audio Layer III |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Restituisce il valore AudioType, che è equivalente all'estensione del nome file, estratta dal nome file specificato |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Nome formale di questo formato audio


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Estensione del nome file (senza il carattere punto) per questo formato audio


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Codice MIME per questo formato audio


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Determina se questa istanza è uguale all'istanza "AudioType" specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Altra istanza AudioType da confrontare con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza è uguale all'oggetto non convertito specificato, che presumibilmente è un'altra istanza di "AudioType"


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza presumibilmente della struct AudioType, che è stata incapsulata in System.Object |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Verifica se due valori "AudioType" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Primo AudioType da verificare |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Secondo AudioType da verificare |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Verifica se due valori "AudioType" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Primo AudioType da verificare |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Secondo AudioType da verificare |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash, che è un numero costante per questo tipo di valore specifico


**Returns:**
int - intero con segno a 4 byte, 0 per valore Undefined

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Valore speciale, che indica un formato audio non definito, sconosciuto o non supportato


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Rappresenta un formato audio MPEG-1 Audio Layer III


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Restituisce il valore AudioType, che è equivalente all'estensione del nome file, estratta dal nome file specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome file | java.lang.String | Nome file arbitrario, può essere relativo o un percorso completo |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

