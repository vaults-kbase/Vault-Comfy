

Puisque tu veux garder la mise en page, voici le texte "brut" de notre dernier récapitulatif. **Copie ce bloc de code ci-dessous** et colle-le dans une nouvelle note dans ton coffre Obsidian :

Markdown

```
# 🐱 Guide de Survie ComfyUI (AMD RX 6800)

## 🚀 Scripts de Lancement
- **Mode RAPIDE** : `python main.py --use-split-cross-attention --highvram --force-fp16`
- **Mode UPSCALE** : `python main.py --use-split-cross-attention --normalvram --cpu-vae --force-fp16`

## 🎨 Réglages Denoise (KSampler ID 24)
- **Portraits** : 0.12 - 0.15 (Douceur)
- **Fourrure / Chat** : 0.20 (Ton réglage gagnant)
- **Paysages** : 0.25 - 0.30 (Détails extrêmes)

## 🛠 Configuration Anti-Crash
- **VAE Tiled** : Taille de tuile à **768**.
- **Résolution** : **1536x1536** pour rester sous les 350s.
- **ControlNet** : Touche `M` (Mute) pour libérer 5 Go de VRAM.
```

### Pourquoi c'est génial pour toi ?

En mettant ton coffre sur Drive, tu peux prendre une capture d'écran d'un résultat sur ton PC et la noter immédiatement dans Obsidian. Si un jour tu dois réinstaller ton SSD externe, tous tes réglages précieux pour ta **RX 6800** seront en sécurité dans le cloud.

**Veux-tu que je te prépare un petit guide sur l'installation d'Obsidian en format "Flatpak" sur Ubuntu si tu ne l'as pas encore fait ?**