# Optimisation de l'agencement des biscuits sur un rouleau de pâte

## Description
Ce projet vise à optimiser la disposition de différents types de biscuits sur un rouleau de pâte de 500 unités de longueur. L'objectif est de maximiser l'utilisation de la pâte tout en respectant les contraintes suivantes :

- Éviter les zones contenant des défauts sur le rouleau.
- Empêcher les chevauchements entre les biscuits.
- Respecter les restrictions spécifiques à chaque type de biscuit.

Chaque biscuit a des caractéristiques propres, telles que sa taille et ses exigences de positionnement.

## Installation

1. Clonez le dépôt :
   ```bash
   git clone <URL_DU_DEPOT>
   cd <NOM_DU_DEPOT>
   ```

2. Installez les dépendances requises :
   ```bash
   pip install -r requirements.txt
   ```

3. Lancez le projet dans un environnement Jupyter Notebook :
   ```bash
   jupyter notebook Projectv2.ipynb
   ```

## Utilisation

1. Ouvrez le fichier `Projectv2.ipynb` dans Jupyter Notebook.
2. Exécutez les cellules de code dans l'ordre pour importer les défauts, configurer les paramètres des biscuits, et lancer l'algorithme d'optimisation.
3. Les résultats incluent :
   - Une représentation visuelle de la disposition des biscuits sur le rouleau.
   - Les statistiques de performance (longueur utilisée, gaspillage, etc.).

## Exemples de résultats

Voici quelques exemples de visualisations générées par le projet :

### Exemple 1 : Disposition optimisée
![Exemple 1](path/to/screenshot1.png)

### Exemple 2 : Zones de défauts et gaspillage
![Exemple 2](path/to/screenshot2.png)

Remplacez les chemins vers les images par vos propres captures d'écran.

## Contributions

Les contributions sont les bienvenues ! Veuillez suivre les étapes suivantes :

1. Forkez le dépôt.
2. Créez une branche pour votre fonctionnalité ou correction de bug :
   ```bash
   git checkout -b ma-fonctionnalite
   ```
3. Faites vos modifications et commitez-les :
   ```bash
   git commit -m "Ajout de ma fonctionnalité"
   ```
4. Poussez les modifications vers votre branche :
   ```bash
   git push origin ma-fonctionnalite
   ```
5. Ouvrez une pull request.

## License

Ce projet est sous licence MIT. Veuillez consulter le fichier `LICENSE` pour plus de détails.
