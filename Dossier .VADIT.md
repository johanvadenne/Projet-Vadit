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
la différence entre chaque fichier et dossier