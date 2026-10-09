---
title: "InvalidImageFormatException"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "L'eccezione che viene lanciata quando si tenta di aprire, caricare, salvare o elaborare in qualche modo del contenuto che presumibilmente è un'immagine raster o vettoriale ma in realtà è un'immagine di tipo inatteso o non è affatto un'immagine."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

L'eccezione che viene lanciata quando si tenta di aprire, caricare, salvare o elaborare
in qualche altro modo del contenuto, che presumibilmente è un'immagine (raster o vettoriale),
ma in realtà è un'immagine di tipo inatteso o non è affatto un'immagine.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Crea una nuova istanza di InvalidImageFormatException con il messaggio di errore specificato |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Crea una nuova istanza di InvalidImageFormatException con il messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Crea una nuova istanza di InvalidImageFormatException con il messaggio di errore specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Messaggio testuale, che descrive l'errore, può essere nullo o vuoto |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Crea una nuova istanza di InvalidImageFormatException con il messaggio di errore specificato e un riferimento all'eccezione interna che è la causa di questa eccezione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Messaggio testuale, che descrive l'errore, può essere nullo o vuoto |
|
|  | innerException | java.lang.RuntimeException | L'eccezione che è la causa dell'eccezione corrente, o un riferimento nullo se non è specificata alcuna eccezione interna. |
|

