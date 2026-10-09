---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επεκτείνει το πρότυπο interface IDisposable, επιτρέποντας την απόκτηση της τρέχουσας κατάστασης ενός αντικειμένου και την εγγραφή στο γεγονός διαγραφής"
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Επεκτείνει το πρότυπο interface IDisposable, επιτρέπει την απόκτηση μιας τρέχουσας
κατάστασης ενός αντικειμένου και την εγγραφή στο γεγονός διαγραφής

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Disposed](#Disposed) | Συμβαίνει όταν το αντικείμενο διαγραφεί |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Καθορίζει αν ένας πόρος είναι κλειστός (true) ή όχι (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Συμβαίνει όταν το αντικείμενο διαγραφεί


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Καθορίζει αν ένας πόρος είναι κλειστός (true) ή όχι (false


**Returns:**
boolean
