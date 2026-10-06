---
title: "IAuxDisposable"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επεκτείνει το πρότυπο διασύνδεση IDisposable, επιτρέπει την απόκτηση της τρέχουσας κατάστασης ενός αντικειμένου και την εγγραφή σε γεγονός αποδέσμευσης"
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Επεκτείνει το πρότυπο διασύνδεση IDisposable, επιτρέπει την απόκτηση μιας τρέχουσας
κατάσταση ενός αντικειμένου και εγγραφή στο γεγονός αποδέσμευσης

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Disposed](#Disposed) | Συμβαίνει όταν το αντικείμενο αποδεσμεύεται |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Καθορίζει εάν ένας πόρος είναι κλειστός (true) ή όχι (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Συμβαίνει όταν το αντικείμενο αποδεσμεύεται


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Καθορίζει εάν ένας πόρος είναι κλειστός (true) ή όχι (false


**Returns:**
boolean
