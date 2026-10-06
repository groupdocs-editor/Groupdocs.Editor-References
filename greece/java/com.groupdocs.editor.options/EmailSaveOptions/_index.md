---
title: "EmailSaveOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη δημιουργία και αποθήκευση εγγράφων ηλεκτρονικού ταχυδρομείου"
type: docs
weight: 15
url: /el/java/com.groupdocs.editor.options/emailsaveoptions/
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
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) με |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Επιτρέπει τον έλεγχο ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Επιτρέπει τον έλεγχο ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) με
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mailMessageOutput | int | Η έξοδος μηνύματος ηλεκτρονικού ταχυδρομείου, η οποία μπορεί επίσης να καθοριστεί μέσω της ιδιότητας |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Επιτρέπει τον έλεγχο ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Τιμή: Σημαδωμένος enum που ελέγχει τα τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Επιτρέπει τον έλεγχο ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο τελικό έγγραφο email, το οποίο θα δημιουργηθεί και αποθηκευτεί με τη μέθοδο [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Τιμή: Σημαδωμένος enum που ελέγχει τα τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι MailMessageOutput.All


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

