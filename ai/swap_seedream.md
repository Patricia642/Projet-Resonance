# Swap de visage avec un modèle Freepik

## Résumé
* Objectif : utiliser un **modèle de personnage entraîné** (ex. `@sarah`) pour **remplacer uniquement le visage + les cheveux** dans une image de base (`@img1`), sans toucher au décor ni aux vêtements.
 * Image de base : `@img1`  
 * Modèle utilisé : `@sarah`  
 * Ce qui change : **visage + cheveux uniquement**  
 * Ce qui reste identique : **décor, vêtements, cadrage, lumière**

### 🛠️ Swap de visage avec modèle Freepik (procédure courte)
* Entraîner un modèle de personnage avec peu d’images (plus stable)
  * Rassembler 3 images du même visage  
  * Créer et lancer l’entraînement du modèle (ex. `@sarah`)

* Entraîner un modèle de personnage avec davantage d’images (moins stable)
  * Rassembler 10–30 images du même visage  
  * Créer et lancer l’entraînement du modèle (ex. `@sarah`)

* Insérer `@img1` comme image de départ dans l’interface  
  * Choisir une photo nette avec le visage bien visible → `@img1`

* Sélectionner le modèle de personnage  
  * Utiliser ton modèle entraîné (`@sarah`)

* Utiliser ce prompt (adapter les noms si nécessaire) :
  * Prompt :

    ```
    Dans @img1, remplace uniquement le visage et les cheveux de la femme par le visage et les cheveux de @sarah.
    Conserve la même position de la tête, le même angle de vue, la même expression générale,
    la même structure du visage, la même direction de la lumière et des ombres.

    Ne modifie pas le background : garde le décor, les couleurs, la perspective, la lumière ambiante,
    les vêtements, la composition et le cadrage exactement tels quels.
    Aucun changement d’environnement, aucun ajout ou retrait d’élément visuel.

    Intègre @sarah de manière réaliste, sans déformation ni mélange.
    Aucun hybride, aucune fusion, aucune interprétation artistique.
    Use strong identity matching, Face Lock ON.
    Fully override the original face with the exact facial identity and hair of @sarah.
    ```
