---
title: "TextDirection"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά 3 πιθανές παραλλαγές για το πώς να αντιμετωπιστεί η κατεύθυνση κειμένου σε έγγραφα απλού κειμένου."
type: docs
weight: 38
url: /el/nodejs-java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Αναπαριστά 3 πιθανές παραλλαγές για το πώς να αντιμετωπιστεί η κατεύθυνση κειμένου σε απλό κείμενο.
έγγραφα

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Κατεύθυνση αριστερά προς δεξιά, συνηθισμένο κείμενο, προεπιλεγμένη τιμή. |
|
|  | [RightToLeft](#RightToLeft) | Κατεύθυνση από δεξιά προς αριστερά |
|
|  | [Auto](#Auto) | Αυτόματη ανίχνευση κατεύθυνσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Κατεύθυνση αριστερά προς δεξιά, συνηθισμένο κείμενο, προεπιλεγμένη τιμή.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Κατεύθυνση από δεξιά προς αριστερά


### Auto {#Auto}
```
public static final int Auto
```


Αυτόματη ανίχνευση κατεύθυνσης. Όταν αυτή η επιλογή είναι ενεργοποιημένη και το κείμενο περιέχει
χαρακτήρες που ανήκουν σε σενάρια RTL, η κατεύθυνση του εγγράφου θα οριστεί
αυτόματα σε RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
