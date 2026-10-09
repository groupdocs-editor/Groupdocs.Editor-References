---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων ηλεκτρονικού ταχυδρομείου"
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων ηλεκτρονικού ταχυδρομείου (email)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), όπου όλες οι επιλογές έχουν οριστεί στις προεπιλεγμένες τιμές |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) με |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Επιτρέπει τον έλεγχο του ποιου μέρους του μηνύματος ηλεκτρονικού ταχυδρομείου θα παραδοθεί στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Επιτρέπει τον έλεγχο του ποιου μέρους του μηνύματος ηλεκτρονικού ταχυδρομείου θα παραδοθεί στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), όπου όλες οι επιλογές έχουν οριστεί στις προεπιλεγμένες τιμές


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) με
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mailMessageOutput | int | Η έξοδος του μηνύματος ηλεκτρονικού ταχυδρομείου, η οποία μπορεί επίσης να καθοριστεί μέσω της ιδιότητας |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Επιτρέπει τον έλεγχο του ποιου μέρους του μηνύματος ηλεκτρονικού ταχυδρομείου θα παραδοθεί στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Τιμή: Σημασμένος enum που ελέγχει τα μέρη του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι  MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Επιτρέπει τον έλεγχο του ποιου μέρους του μηνύματος ηλεκτρονικού ταχυδρομείου θα παραδοθεί στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Τιμή: Σημασμένος enum που ελέγχει τα μέρη του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι  MailMessageOutput.All


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

