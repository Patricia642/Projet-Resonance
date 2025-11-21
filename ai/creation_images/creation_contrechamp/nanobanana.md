# Créer un contrechamp dans Nano Banana

## Principe
Objectif : générer un **contrechamp** (reverse shot) à partir d’une image existante (`@img1`) dans Nano Banana, en recréant la scène **depuis le point de vue du personnage**, tout en conservant l’ambiance, le décor et la cohérence visuelle de l’image d’origine.

---

### 🟠 Créer un contrechamp dans Nano Banana

* Préparer l’image  
  * Aller sur : https://flux-context.org/models/nano-banana  
  * Uploader l’image de référence : utiliser `@img1` (ton image actuelle)  
  * Vérifier que la scène d’origine est bien lisible (décor, ambiance, lumière)

* Définir le contrechamp  
  * Préciser que la caméra passe **du côté du personnage**  
  * Décrire un point de vue **depuis ses yeux** ou sa **position exacte**  
  * Indiquer les éléments visibles dans ce nouveau cadre (ex. bol, mains, objets devant)

* Verrouiller la continuité visuelle  
  * Lumière, ambiance, textures, couleurs identiques  
  * Conserver l’environnement : épicerie japonaise 1970s, néons, kanji, vapeur  
  * Maintenir la cohérence stylistique (film, grain, halation, etc.)

* Générer  
  * Coller le prompt  
  * Lancer la génération  
  * Vérifier cohérence : ambiance identique, POV clair, bonne perspective  
  * Ajuster si nécessaire (distance, angle, composition)

---

# Exemple de prompt prêt à copier-coller — Contrechamp top-down (bol + mains)

* Utiliser ce prompt (adapter les noms si nécessaire) :
  * Prompt :

    ```
    Use @img1 as reference, but change the camera angle to a close-up top-down 
    perspective from the woman’s point of view. Show the steaming soup bowl in 
    the center, her hands visible holding chopsticks, and the snake clearly 
    present near the bowl.

    The composition must feel intimate and cinematic, as if we are seeing 
    through her eyes. Keep the same chaotic 1970s Japanese grocery store 
    environment illuminated by colorful neon lights and kanji shop signs.

    Maintain the Gregory Crewdson–style cinematic lighting, FujiFilm 400H tones, 
    soft halation, pastel highlights, subtle film grain, and realistic glossy 
    textures.

    ```

---

# Exemple de prompt prêt à copier-coller — Contrechamp « regard vers la salle »

* Utiliser ce prompt (adapter les noms si nécessaire) :
  * Prompt :

    ```
    From @img1 create the reverse shot from the woman’s point of view. Show the 
    rest of the restaurant, including the open kitchen in the background, and a 
    few unusual, eccentric people seated at other tables, eating.

    Inside a chaotic 1970s Japanese diner or grocery-style restaurant illuminated 
    by colorful neon lights and kanji shop signs, the space feels alive and detailed 
    — steaming pots, hanging utensils, flickering reflections everywhere.

    Blend Gregory Crewdson’s cinematic realism with vintage luxury advertising 
    aesthetics: controlled studio lighting, soft frontal flash, refined composition, 
    desaturated FujiFilm 400H tones, subtle halation, and gentle film grain.

    The camera is positioned at eye level, simulating the woman’s gaze, with shallow 
    depth of field focusing on the mid-space (tables and figures). Retro luxury campaign 
    atmosphere, cinematic realism, emotional narrative tone, high-end editorial lighting, 
    soft fill light, realistic textures, 50 mm lens look, professional color grading.

    ```
