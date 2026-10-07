---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "L'eccezione che viene lanciata quando si tenta di aprire, caricare, salvare o elaborare in qualche modo del contenuto che presumibilmente è un font di formato supportato noto, ma in realtà è un font di formato non supportato o inatteso o non è affatto un font."
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

L'eccezione che viene sollevata quando si tenta di aprire, caricare, salvare o elaborare in qualche modo del contenuto, che presumibilmente è un font in un formato supportato (noto), ma in realtà è un font in un formato non supportato o inatteso o non è affatto un font.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Crea una nuova istanza di con il messaggio di errore specificato |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Crea una nuova istanza di @see \"InvalidFontFormatException\" con il messaggio di errore specificato e un riferimento all'innerException che è la causa di questa eccezione |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Crea una nuova istanza di con il messaggio di errore specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Messaggio testuale, che descrive l'errore, può essere nullo o vuoto |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Crea una nuova istanza di @see \"InvalidFontFormatException\" con il messaggio di errore specificato e un riferimento all'innerException che è la causa di questa eccezione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Messaggio testuale, che descrive l'errore, può essere nullo o vuoto |
|
|  | innerException | java.lang.RuntimeException | L'eccezione che è la causa dell'eccezione corrente, o un riferimento nullo se non è specificata alcuna innerException. |
|

