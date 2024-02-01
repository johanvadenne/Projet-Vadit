## `.VADIT/local`
il contient un fichier JSON qui recence tous les fichiers existants en partant de la dernier version. le fichier JSON va enregistrer ceci:
```json
{
  "dossier/fichier.txt": 
  {
    "date_dernière_modification": "11/10/2023 11:20:22",
    "SHA256": "140934990f93bda1a500ff7fed7f5b7eb00d25f84cdd7cef49ce54fb96d0661b"
  }
}
```
CLÉ: *chemin relative du fichier par rapport au dépôt*: permet d'identifier le fichier dans le dépôt
VALEUR:
- *date_dernière_modification*: permet de vérifié la dernière date de modification du fichier pour savoir si il à été modifier.
- *SHA256*: Si *date_dernière_modification* à été modifier on vas vérifier le contenue du fichier en comparant en le hachant et le comparant avec le *SHA256*.