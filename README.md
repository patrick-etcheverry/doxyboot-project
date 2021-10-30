### Présentation

Doxyboot-project est un projet Doxygen pré-configuré qui intègre le framework Bootstrap afin de générer une documentation html avec un rendu "moderne".
### Pré-requis
Pour utiliser Doxyboot, les pré-requis suivants sont nécessaires :
- disposer d'une connexion internet ;
- avoir installé Doxygen sur sa machine.

### Utilisation
- clôner ou télécharger ce *repository*.
- placer les codes source documentés avec Doxygen dans le dossier *src*
- personnaliser (optionnel) le logo situé dans le dossier */doxygen/img* (fichier png uniquement, sinon nécessité d'adapter le tag *PROJECT_LOGO* du fichier *Doxyfile*).
- générer la documentation via la commande suivante:
``` bash
cd doxygen
doxygen
```
- la documentation html est alors générée dans le dossier **doc** du projet.


### Aperçu du type de résultat obtenu

![Aperçu du résultat obtenu](screenshot.png)


