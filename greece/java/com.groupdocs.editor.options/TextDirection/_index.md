---
title: "TextDirection"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά 3 πιθανές παραλλαγές για το πώς να αντιμετωπίζεται η κατεύθυνση κειμένου σε απλά κείμενα εγγράφων"
type: docs
weight: 38
url: /el/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Αναπαριστά 3 πιθανές παραλλαγές για το πώς να αντιμετωπίζεται η κατεύθυνση κειμένου σε απλό κείμενο
έγγραφα

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Κατεύθυνση αριστερά προς δεξιά, συνηθισμένο κείμενο, προεπιλεγμένη τιμή. |
|
|  | [RightToLeft](#RightToLeft) | Κατεύθυνση δεξιά προς αριστερά |
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


Κατεύθυνση δεξιά προς αριστερά


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
