# Noir Absolu / Absolute Black

A true-black AMOLED theme for Discord with readable surfaces, compact scrollbars, clear interactive states, and a customizable accent color.  
Un thème Discord AMOLED en noir absolu, avec des surfaces lisibles, des barres de défilement compactes, des états interactifs clairs et une couleur d’accent personnalisable.

## Download / Téléchargement

Download [`Noir-Absolu.theme.css`](./Noir-Absolu.theme.css). This is the only theme file required.  
Téléchargez [`Noir-Absolu.theme.css`](./Noir-Absolu.theme.css). C’est le seul fichier de thème nécessaire.

## Features / Fonctionnalités

- True OLED black (`#000000`) across Discord’s main surfaces
- Neutral raised surfaces that keep text, controls, and popouts readable
- Custom styling for links, mentions, replies, selections, buttons, borders, and focus states
- Compact scrollbars and a completely black voice/user panel area
- One configurable accent with eight ready-to-use presets
- Compatible with BetterDiscord and Vencord
- No remote CSS imports

## Installation

### BetterDiscord

1. Download `Noir-Absolu.theme.css`.
2. Open `Discord Settings > BetterDiscord > Themes`.
3. Place the file in the themes folder and enable **Noir Absolu - Absolute Black**.

### Vencord

1. Téléchargez `Noir-Absolu.theme.css`.
2. Ouvrez `Paramètres Discord > Vencord > Themes`.
3. Placez le fichier dans le dossier des thèmes, puis activez **Noir Absolu - Absolute Black**.

## Accent presets / Préréglages de couleur

Violet is enabled by default. To keep your choice across theme updates, paste one preset into BetterDiscord **Custom CSS** or Vencord **QuickCSS**.  
Le violet est activé par défaut. Pour conserver votre choix après les mises à jour, collez un préréglage dans le **Custom CSS** de BetterDiscord ou le **QuickCSS** de Vencord.

| Preset / Préréglage | Hue / Teinte | Saturation | Lightness / Luminosité | Reference |
|---|---:|---:|---:|---:|
| Violet / Purple | `264` | `100%` | `72%` | `#a970ff` |
| Bleu / Blue | `210` | `100%` | `66%` | `#52a8ff` |
| Rouge / Red | `352` | `100%` | `68%` | `#ff5c73` |
| Orange | `24` | `100%` | `62%` | `#ff8a3d` |
| Jaune / Yellow | `45` | `86%` | `62%` | `#f2c94c` |
| Vert / Green | `150` | `68%` | `54%` | `#39d98a` |
| Cyan | `187` | `78%` | `55%` | `#35d0e6` |
| Rose / Pink | `329` | `100%` | `69%` | `#ff5fb2` |

Replace the three values below with the row you want.  
Remplacez les trois valeurs ci-dessous par celles de la ligne souhaitée.

```css
:root {
  --noir-accent-hue: 264;
  --noir-accent-saturation: 100%;
  --noir-accent-lightness: 72%;
}
```

## Credits / Crédits

Created by / Créé par **woozyfps.**  
[wooptimisation.pro](https://wooptimisation.pro)
