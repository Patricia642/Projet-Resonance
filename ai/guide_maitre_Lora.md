# Guide maître / Lora

## Rassembler les images  
Préparer **10 à 30 images** du même personnage.

- Variété recommandée :
  - angles différents  
  - expressions variées  
  - lumière changeante  
  - plans rapprochés + quelques plans moyens
- Qualité attendue : **haute résolution**, pas floues, pas surtraitées.

## Uploader les images dans l’interface [LoRA Trainer](https://fal.ai/models/fal-ai/flux-lora-portrait-trainer)
Importer le dossier d’images dans la section **training dataset**.

## Choisir un nom de LoRA + Trigger Word  
Définir un mot-clé associé au personnage (utilisé ensuite dans les prompts).

Exemples :  
`mila_portrait`  
`mila_face`

## Lancer la génération du LoRA  
Le système entraîne ton fichier LoRA.

Sortie finale :  
`mila_character_lora_v1.safetensors`

## Tester le LoRA  
Avant intégration :

- Faire **3–4 prompts test**  
- Vérifier que **le visage est stable**  
- Vérifier la bonne réponse au **trigger word**

---

# Utilisation du LoRA

## Étape 1 – Préparer ton entrée (prompt + scène + triggers)  
Décrire clairement la scène et intégrer les **trigger words** dans la description.

## Étape 2 – Importer les LoRA (.safetensors) + Image de référence  

1. Copier le **lien du `.safetensors`** dans le path.
2. Régler le
