## engager (commit)
Permet de répertorier chaque fichier et dossier qui vont être modifier dans un fichier JSON.
exemple:
```json
{
  "supprimer":
  {
    "fichier":["fichier1", "fichier2", "fichier3"],
    "dossier":["dossier1"]
  },
  "modifier":
  {
    "fichier":["fichier4", "fichier5", "fichier6"],
    "dossier":["dossier2"]
  },
  "ajouter":
  {
    "fichier":["fichier7", "fichier8", "fichier9"],
    "dossier":["dossier3"]
  }
}
```

## différentiel
Permet de répertorier dans des sous-dossier ayant le même nom de l'engagement (commit)
la différence entre chaque fichier et dossier. (Un enregistrement différentiel)

## SHA256/engager
Permet de répertorier des fichiers JSON ayant le même nom de l'engagement (commit).
Il permet d'enregistrer le SHA256 du fichier

## SHA256/local
Contient un fichier JSON qui répertorie le SHA256 de chaque fichier.