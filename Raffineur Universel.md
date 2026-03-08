WF: Raffineur Universel_WF.json

Checkpoint : sd-xl-base.1.0
Nodes: ImageUpscaleWithModel, ImageScale, VAEEncodeTiled

Lorsque vous serez prêt, supprimez cette note et faites ce coffre vôtre.
### 1\. Pour les Portraits (Peau humaine)

Le réglage de **0.20** que tu utilises pour le chat risque de créer un effet "grain de peau" trop prononcé ou des micro-défauts sur un visage.

-   **Denoise** : Descends à **0.12 - 0.15**. Cela préservera la douceur de la peau tout en rendant les cils et les iris très nets.
    
-   **Modèle d'Upscale** : Le `RealESRGAN_x4plus` est bon, mais si tu as accès à un modèle type `4x-UltraSharp`, il est souvent plus respectueux des textures de peau.
    

### 2\. Pour les Paysages

Ici, tu peux être beaucoup plus agressif car les textures naturelles (roches, herbe, nuages) supportent bien les détails ajoutés.

-   **Denoise** : Tu peux monter à **0.25 - 0.30**.
    
-   **Effet** : L'IA va littéralement "sculpter" des détails dans les feuillages ou les fissures des rochers qui n'existaient pas sur l'image originale.
    

 

___

### Tableau Récapitulatif des Réglages (KSampler ID 24)

| Sujet | Denoise Idéal | Steps conseillés | Résultat attendu |
| --- | --- | --- | --- |
| **Fourrure / Animaux** | **0.20** | 25 | Poils fins et brillants |
| **Portraits** | **0.15** | 20-25 | Regard intense, peau naturelle |
| **Paysages** | **0.30** | 30 | Profondeur et micro-détails |
| **Architecture / Objets** | **0.10** | 20 | Lignes droites et surfaces propres |