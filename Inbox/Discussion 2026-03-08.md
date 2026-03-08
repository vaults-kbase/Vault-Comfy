# Discussion IA 2026-03-08

## Source: 
uickAdd traite le clipboard comme texte brut (pas HTML/Markdown riche des IA), d'où perte formatage ; c'est limitation connue, pas mal paramétré. Solution 1: MarkDownload Priorité  MarkDownload préserve Markdown natif IA (meilleur pour Perplexity/Claude) → .md Inbox direct formaté → QuickAdd pour texte simple. Solution 2: Extension Copy Markdown  Installe Firefox "Copy as Markdown - Clipboard" : clic droit sur fil IA → "Copy as Markdown" → Ctrl+V Obsidian/QuickAdd préserve format !​ Solution 3: Macro QuickAdd Avancée  QuickAdd Settings → Add Choice → Macro → Add "Paste with format" (si v récente) ou script JS clipboard HTML→MD, mais complexe.

Tags: #IA #capture #Obsidian

## Solution 3: Macro QuickAdd Avancée

QuickAdd Settings → Add Choice → **Macro** → Add "Paste with format" (si v récente) ou script JS clipboard HTML→MD, mais complexe.[quickadd.obsidian](https://quickadd.obsidian.guide/docs/Choices/MacroChoice/)

## Recommandé

Utilise **MarkDownload** pour 90% cas (format parfait) + QuickAdd texte brut + édition rapide tags.

Test Copy as Markdown extension ?

![favicon forum.obsidian.md](https://www.google.com/s2/favicons?sz=128&domain=forum.obsidian.md)

![favicon quickadd.obsidian.guide](https://www.google.com/s2/favicons?sz=128&domain=quickadd.obsidian.guide)

![favicon github.com](https://www.google.com/s2/favicons?sz=128&domain=github.com)

17 sources

oui MarkDownload - Markdown Web Clipper est installé dans FF

15 sources examinées

Parfait, MarkDownload est installé et préserve le format Markdown des IA (meilleur que QuickAdd pour discussions complètes).obsidian+1

## Config MarkDownload FF

Clic droit icône → **Manage Extension** → **Options/Preferences**.[addons.mozilla](https://addons.mozilla.org/en-US/firefox/addon/markdownload/)

-   **Always show Save As**: OFF
    
-   **Download Images**: ON (pour images IA)
    
-   **Enable Obsidian Integration**: ON, **Vault**: Vault-Comfy, **Folder**: Inbox