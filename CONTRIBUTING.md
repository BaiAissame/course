
---

### Guide de Contribution


```md

Avant de contribuer, veuillez suivre les étapes ci-dessous pour assurer un workflow fluide et bien organisé.

## Règles générales
✔️ Chaque modification doit être associée à une **issue**  
✔️ Toute contribution passe par une **Pull Request (PR)**  
✔️ Les commits doivent être **signés** (`git commit -S`)  
✔️ Respecter le format du fichier `liste_courses.txt` (éviter les doublons)  
✔️ Ne pas modifier `main` directement (utiliser des branches `feature/`)  

## Étapes pour contribuer

### **Créer une issue**
Avant de modifier la liste, **créez une issue** dans l'onglet [Issues](https://github.com/BaiAissame/course/issues) avec :
- Un titre clair (`Ajout de légumes`, `Suppression des produits périmés`)
- Une description détaillée
- Une checklist des actions à faire

### **Créer une branche**
Utilisez le nom correspondant à l’issue :
```sh
git checkout -b feature/ajout-legumes
