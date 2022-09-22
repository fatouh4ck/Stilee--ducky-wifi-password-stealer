# Stilee

### Configurer le script

A script that steal wifi passwords on a Windows computer.

Vous devez remplacer `EMAIL-SENDER` par l'adresse OUTLOOK qui va envoyer le *.zip* et `EMAIL-RECEIVER` par l'adresse mail (n'importe laquelle) qui va le recevoir.

---
### Le script va (dans l'ordre) :

- ouvrir un cmd et réduire sa taille
- créer un dossier "A" sur le Bureau
- exporter les mots de passe dans ce dossier
- Compresser le dossier en A.zip (toujours sur le bureau) 
- envoyer le zip à l'adresse mail choisie au préalable avec Outlook SMTP
- supprimer les logs, le dossier et l'archive zip.
- (ouvrir un notepad et y écrire que tout c'est bien passé (il se fermera tout seul au bout de 3s))
- (faire clignoter la LED 3 fois)
