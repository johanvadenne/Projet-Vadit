## `.VADIT/local`
il contient un fichier JSON qui recence tous les fichiers existants en partant de la dernier version. le fichier JSON va enregistrer ceci:
```json
{
    "C:\\Users\\j.vadenne\\Desktop\\Dépôt VADIT 2.0\\Dépôt 1\\test.txt": {
        "DossierOuFichier": "FICHIER",
        "Chemin": "C:\\Users\\j.vadenne\\Desktop\\Dépôt VADIT 2.0\\Dépôt 1\\test.txt",
        "CheminRelative": "test.txt",
        "Date": "31/01/2024 13:04:02",
        "sha256": ""
    },
    "C:\\Users\\j.vadenne\\Desktop\\Dépôt VADIT 2.0\\Dépôt 1\\test2.txt": {
        "DossierOuFichier": "FICHIER",
        "Chemin": "C:\\Users\\j.vadenne\\Desktop\\Dépôt VADIT 2.0\\Dépôt 1\\test2.txt",
        "CheminRelative": "test2.txt",
        "Date": "31/01/2024 13:10:53",
        "sha256": ""
    }
}
```
CLÉ: *chemin relative du fichier par rapport au dépôt*: permet d'identifier le fichier dans le dépôt
VALEUR:
- *date_dernière_modification*: permet de vérifié la dernière date de modification du fichier pour savoir si il à été modifier.
- *SHA256*: Si *date_dernière_modification* à été modifier on vas vérifier le contenue du fichier en comparant en le hachant et le comparant avec le *SHA256*.