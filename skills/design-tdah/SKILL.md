---
name: design-tdah
version: 1.0.0
description: Concevoir une page, une app, un tableau de bord ou un tunnel pour un cerveau TDAH, dans le style « feuille sur table » de Mike IA. À utiliser dès qu'on dessine ou refait un écran, un formulaire, une page de vente, un tableau de bord, un onboarding, une page d'accueil, ou qu'on dit « design TDAH », « charge mentale », « cécité temporelle », « une seule action », « trop d'éléments », « style livre », « feuille blanche ». Pas pour un simple changement de couleur sans contexte TDAH.
license: MIT
author: Mike Builds IA — mikeia.com
metadata:
  tags: [tdah, adhd, design, ux, accessibilite, neurodivergent, style-livre]
  category: design
  inspire-de: adhd-design-expert (curiositech/some_claude_skills, MIT), relu, traduit et marié au style de Mike IA le 22 octobre 2026
---

# design-tdah — concevoir pour un cerveau TDAH, dans le style « feuille sur table »

Tu conçois des écrans pour des gens dont la mémoire de travail est courte, qui ne
sentent pas le temps passer, qui ont du mal à démarrer, et qui décrochent dès que
l'écran en demande trop. Ce n'est pas un défaut à corriger : c'est le cahier des
charges. Deux moitiés dans cette skill : **ce qu'il faut faire** (les cinq
principes) et **à quoi ça ressemble** (le style). Les deux ensemble, toujours.

## Quand l'utiliser

- dessiner ou refaire une page, une app, un tableau de bord, un onboarding, un
  formulaire, une page de vente, un email long ;
- relire un écran avant de le livrer (la check-list en bas) ;
- quand on te dit « c'est trop », « je ne sais pas où cliquer », « je ne vois
  pas où j'en suis », « je n'ouvre plus l'app ».

Pas pour : l'accessibilité WCAG seule, ou une retouche de couleur sans contexte.

## Ce que le TDAH change, en cinq lignes

| Ce qui se passe dans la tête | Ce que l'écran doit faire |
|---|---|
| Mémoire de travail courte (3 à 5 choses, pas 7) | Une action par écran, étapes guidées, jamais 50 cases |
| Cécité temporelle (« bientôt » ne veut rien dire) | Compte à rebours, barre, pourcentage, « il reste N jours » |
| Démarrer est le plus dur | Le premier pas évident, petit, écrit |
| Dopamine rare | Retour immédiat, victoires visibles, trophées qui restent |
| Hors de vue = hors de tête | Tout l'important reste visible, pas de menu caché |
| Sensibilité au rejet | Jamais de reproche, toujours une sortie |

## Les cinq principes

### 1. Réduire la charge, sans pitié
- **Une seule action principale par écran.** Si tu en as deux, tu as deux écrans.
- Étapes guidées plutôt qu'un long formulaire. Choix par défaut déjà cochés.
- Trois à quatre options maximum, avec une étiquette « conseillé ».
- Un « tu es ici » permanent : étape 2 sur 3, page 4 sur 9.

### 2. Rendre le temps concret
- Jamais « quelques minutes », « bientôt », « chargement… ». Toujours un nombre :
  « 2 min 40 », « jour 22 sur 31 », « attendu dans 40 jours », « 87 % du chemin ».
- Un long traitement montre une barre ET le temps écoulé ET le temps restant.
- Une tâche longue se découpe en blocs datés : « 3 fois 15 min ».

### 3. Tout garder visible
- Pas de menu hamburger pour l'essentiel. Les chiffres clés, l'à-faire, l'état :
  à l'écran, toujours au même endroit.
- Le détail d'une carte **prend la place des autres cartes**, pas un dépliant ni
  une fenêtre par-dessus.
- Positions stables d'une visite à l'autre : le cerveau apprend l'espace.

### 4. Pardonner
- Jamais « série brisée », « objectif manqué », « 0 jour ». À la place :
  « 6 jours sur 7, ça tient », « rattrapable : il reste 10 jours ».
- Un « Annuler » après chaque action, quelques secondes, bien visible.
- Une phrase qui donne toujours une sortie : dire ce qui manque ET comment l'avoir.
- Un trophée gagné ne se perd jamais, même si le mois suivant retombe.

### 5. Célébrer
- Retour immédiat à chaque fin de tâche : la ligne qui glisse, le chiffre qui monte,
  des confettis à la vraie victoire.
- Des trophées **permanents** : gagnés en plein, les prochains en pointillés avec
  ce qu'il manque (« encore 3 ventes »). Le prochain visible, c'est la prochaine
  petite marche.
- Un niveau ou des points qui ne redescendent jamais : la mémoire de ce qui a été
  fait, même un mois à zéro ne l'efface pas.
- La règle : **on récompense le jour réussi, on ne punit jamais le jour raté.**
  Un compteur de série punit ; un trophée récompense.

## Le style « feuille sur table »

Les principes disent quoi, le style dit comment, sans surcharger. Partir de ces
réglages avant d'ouvrir n'importe quelle autre skill de design.

**La scène** : une **feuille blanche** posée sur une **table gris chaud**.
```
fond (table)      #f3f1ec        mode nuit : #121110
papier (feuille)  #ffffff        mode nuit : #1d1c19
encre             #1b1a17        mode nuit : #efece5
encre secondaire  #6f6b63        mode nuit : #a39f95
encre discrète    #8b877e        mode nuit : #8e8a80
filet             #e6e3dc        mode nuit : #2d2b27
accent (un seul)  #1f7a4d        mode nuit : #3ddc84   ← l'argent, le progrès, le gagné
feuille           rayon 22 px, ombre très douce et longue :
                  0 1px 2px rgba(30,25,15,.05), 0 18px 48px -24px rgba(30,25,15,.25)
```
- **Une seule couleur d'accent.** Par défaut le vert foncé ci-dessus. Si la marque
  en a une, la sienne, et une seule. Jamais fluo, jamais deux.
- **Le vide fait le design** : marges larges, 44 px entre deux sections, 60
  caractères par ligne maximum, 17 px de texte, interligne 1,55.
- **Typo** : titres en gras serré (Open Sauce Sans 800 ou Sora, lettrage −0,02 em),
  texte Instrument Sans ou Manrope, **étiquettes en monospace** petites (11 px),
  capitales espacées (`letter-spacing: .12em`).
- **Titre en deux tailles** : le plat en gros et gras, le complément dessous, plus
  petit et gris.
- **Chiffres clés en grand** (26 à 32 px) avec l'étiquette mono au-dessus et une
  sous-ligne mono grise en dessous (« 36 ventes · net »).
- **Barres de progression** : un filet de 3 px, dans l'accent, sur le filet gris.
- Listes illustrées par des **emoji** dans une grille ; étapes numérotées en gros,
  dans l'accent.
- Cartes en grille (image 4:3 puis corps) ou cartes larges (image à gauche,
  colonnes séparées par un filet). Le détail prend la place des autres cartes.
- Boutons : pilule, bord filet, 13 px gras ; le bouton principal plein encre.
- **Interdits** : dégradés, « bento » d'encadrés, coins arrondis partout, ombres
  dures, fond sombre par défaut, emoji dans les titres, second accent.
- Mode nuit : mêmes règles, feuille sombre sur table plus sombre, jamais du noir pur.

## Un écran type (la page d'accueil d'un entrepreneur)

```
jeudi 22 octobre                                        ☾

Bonjour Mike.
À ce rythme, 1,5 k€ tombe à la fin du mois. Continue de marcher.

AUJOURD'HUI        CE MOIS                 PROCHAIN PALIER
0 €                1 300 €                 200 €
0 vente            36 ventes · net         ≈ 6 ventes à 36 €
                   ▬▬▬▬▬▬▬▬▬▬▬▬▬░░░░░       ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬░░
                   jour 22 sur 31 ·        1,5 k€ attendu dans 40 jours
                   il reste 10 jours       · 87 % du chemin

LA SEULE CHOSE AUJOURD'HUI
┌──────────────────────────────────────────────────────────┐
│ Écrire l'intro de la page de vente              [ Fait ] │
│ 1  Commence par : ouvre le brouillon. 2 minutes.         │
│ 15:00  ▬▬▬░░░░░░░░░░   5 min · 15 min · 25 min · Lance   │
└──────────────────────────────────────────────────────────┘

TROPHÉES — 5 sur 13. Le prochain est à portée.
🥇 Première vente   💶 Mois à 3 chiffres   ⬚ 50 ventes (encore 14)
```

## Check-list avant de livrer

- [ ] La tâche principale se fait en 3 clics ou moins ?
- [ ] Le temps est un nombre partout (jamais « bientôt », « quelques minutes ») ?
- [ ] Une fin de tâche déclenche un retour visible ?
- [ ] L'action principale saute aux yeux, et il n'y en a qu'une ?
- [ ] Toute erreur s'annule ?
- [ ] Aucune phrase ne fait honte ? Chaque manque dit comment l'avoir ?
- [ ] L'important est visible sans ouvrir un menu ?
- [ ] Une seule couleur d'accent ? Du vide autour de chaque chose ?
- [ ] Un trophée gagné reste gagné ?
- [ ] Ça tient sur un téléphone, 16 px de marge, sans défilement horizontal ?

## Anti-patterns

| Ce qu'on voit | Pourquoi c'est faux | À la place |
|---|---|---|
| « Série brisée : 0 jour » | Punit le jour raté, déclenche la sensibilité au rejet | « 6 jours sur 7 cette semaine » |
| L'essentiel dans un sous-menu | Hors de vue = hors de tête | Tout visible, positions fixes |
| « Chargement… », « bientôt » | Sans valeur pour un cerveau qui ne sent pas le temps | Compte à rebours, barre |
| 10 options sans défaut | Paralysie de décision | 3 options, une « conseillée » |
| Badges, XP, confettis qui s'empilent sans règle | Du bruit, plus de dopamine | Des trophées à règle claire, le prochain visible |
| Deux accents, dégradés, bento | Surcharge visuelle | Une feuille, un accent, du vide |

## D'où ça vient

Les cinq principes sont une relecture en français de `adhd-design-expert`
(curiositech/some_claude_skills, MIT), avec un désaccord assumé : la skill
d'origine dit « si un neurotypique trouve ça trop, c'est bon pour le TDAH ».
Ici : **plus de feedback, oui ; plus de décoration, non.** Le style vient de
Mike IA (mikeia.com), l'IA pour les entrepreneurs TDAH.
