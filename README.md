# Stilee

## Deux langues disponibles/two languages availables

Choisissez/choose `payload[FR]` ou/or `payload[EN]` !

---

### Configurer le script

Un script qui récupère les mots de passe wifi sur un ordinateur Windows et qui les envoie par mail.

Vous devez remplacer `EMAIL-SENDER` par l'adresse OUTLOOK qui va envoyer le *.zip* et `EMAIL-RECEIVER` par l'adresse mail (n'importe laquelle) qui va le recevoir.

### Le script va (dans l'ordre)

- ouvrir un cmd et réduire sa taille
- créer un dossier "A" sur le Bureau
- exporter les mots de passe dans ce dossier
- Compresser le dossier en *A.zip* (toujours sur le bureau)
- envoyer le zip à l'adresse mail choisie au préalable avec Outlook SMTP
- supprimer les logs, le dossier et l'archive zip.
- ouvrir un notepad et y écrire que tout c'est bien passé (il se fermera tout seul au bout de 3s) <-- étape facultative

Basé sur le script de @norepository

---

### Configure the script

A script that grabb wifi passwords on a Windows computer and sends them by email.

You need to replace `EMAIL-SENDER` with the OUTLOOK mail address that will send the *.zip* and `EMAIL-RECEIVER` with the email address (any one) that will receive it.

### The script will (in order)

- open a cmd and reduce its size
- create a folder "A" on the desktop
- export the passwords in this folder
- compress the folder to *A.zip* (still on the desktop)
- send the zip to the email address chosen beforehand with Outlook SMTP
- delete the logs, the folder and the zip archive.
- open a notepad and write that everything went well (it will close itself after 3s) <-- optional part

Based on @norepository's script.
