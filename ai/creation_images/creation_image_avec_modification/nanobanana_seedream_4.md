# Variation d'une image dans Nano Banana et Seedream

## Principe
Objectif : réaliser des variations (expression, angle, ajout d’éléments) sur une **image existante**, tout en **préservant strictement la composition et l’identité du sujet**.

---

### 🟠 Intégrer un personnage dans Nano Banana

* Préparer l’image  
  * Aller sur : https://flux-context.org/models/nano-banana  
  * Uploader l’image de référence : `/mnt/data/freepik__upload-reference__17238.png`  
  * Vérifier que le sujet, la lumière et l’ambiance sont bien visibles  

* Définir la modification souhaitée  
  * Expression : sourire, surprise, sérieux…  
  * Angle : légère variation de perspective  
  * Ajout : objet sur la table, accessoire, petit élément de décor  

* Verrouiller la composition  
  * Conserver composition, cadrage, angle caméra, lumière, positions des objets  
  * Ne modifier **que l’élément demandé**  

* Préserver l’identité du sujet  
  * Garder visage, taches de rousseur, cheveux, textures  
  * Préserver manteau vert, vapeur, reflets, ambiance néon  

* Générer  
  * Coller le prompt  
  * Lancer la génération  
  * Vérifier que la composition n’a pas changé  
  * Ajuster si nécessaire  

---

# Exemple de prompt prêt à copier-coller — Changement d’expression

* Utiliser ce prompt (adapter les détails si nécessaire) :
  * Prompt :

    ```
    Use the reference image @img1

    Maintain the exact original composition, framing, camera angle, lighting,
    neon reflections, steam behavior, and scene layout. Preserve the woman's
    facial identity, freckles, red hair color and natural flow, skin texture,
    and the green fur coat with nano-level precision.

    Modify only her facial expression: her smile disappears entirely, her lips tense slightly, and subtle
    fear shows in her eyes through widened pupils and a faint tightening of the eyebrows. Do not change any
    other facial proportions, objects, background elements, or the color palette.
    ```


---

# Exemple de prompt prêt à copier-coller — Changement d’angle

* Utiliser ce prompt (adapter les détails si nécessaire) :
  * Prompt :

    ```
    Use the reference image @img1

    Preserve the woman's exact facial identity, freckles, skin texture, red hair color and natural flow,
    and the green fur coat. Maintain the neon lighting, steam behavior, color palette, and overall atmosphere.
    
    Rebuild the camera perspective to a fully frontal angle: the woman facing directly toward the viewer.
    Reconstruct facial geometry to match a true front-facing view while keeping identity consistent.
    Allow background objects to adjust minimally so the new camera angle feels natural.
    
    Keep the same distance from the camera, same lighting direction, same mood, and same scene layout.
    No duplicate faces. No secondary silhouettes. Only rotate the perspective to a frontal view.

    ```

---

# Exemple de prompt prêt à copier-coller — Ajout d’un élément

* Utiliser ce prompt (adapter les détails si nécessaire) :
  * Prompt :

    ```
    Use the reference image @img1

    Maintain the exact original composition, framing, camera angle, lighting,
    neon reflections, steam, and all object positions. Preserve the woman's face,
    hair, skin, and green fur coat with nano-scale precision. Do not alter any
    existing elements.

    Add a small white porcelain cat figurine on the table, placed between the teapot
    and the bowl. Match the scene lighting, reflections, and shadows so the figurine
    integrates naturally into the environment without drawing focus away from the woman.
    ```
