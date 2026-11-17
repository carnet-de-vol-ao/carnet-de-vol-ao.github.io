# ✈️ Carnet de Vol AO — DCS World

Site : **https://carnet-de-vol-ao.github.io/**

- `index.html` — l'application (tableau de bord, carnet, saisie, sauvegarde, paramétrage).
- `data/carnet.json` — les données du carnet (vols 2025-2026, historique 2008→, listes, réglages). Mis à jour automatiquement par le site quand la sauvegarde en ligne est connectée ; chaque enregistrement crée une version dans l'historique Git.
- `data/Carnet_de_Vol_DCS_2026-11-16.xlsx` — classeur Excel d'origine (archive).

## Apparence & personnalisation
- Menu **Apparence** : 17 thèmes (Cockpit, US NAVY, Modern Warfare, Centre d'opérations, DEFCON 1, Camouflage forêt, Désert — OPEX, Arctique, Furtif, PS5, PC Windows 11 clair/sombre, GAMER, Marine nationale, Vision nocturne, Crépuscule, Clair), couleurs, polices, arrondis, effet verre, filigrane, logo, fond d'écran.
- **Paramétrage → Fenêtres, menus & libellés** (ou bouton « ✏️ Personnaliser l'écran ») : renommer, masquer, réordonner et redimensionner menus, fenêtres et compteurs.
- Tous ces réglages sont enregistrés avec les données (navigateur + sauvegarde GitHub).
- `assets/` : emblème F/A-18 (logo) et icônes du site (favicon).

## Tableau de bord futuriste
- Bandeau « poste de commandement » : horloges locale/Zulu, statut pilote, sélection d'année.
- Compteurs animés avec mini-courbes et tendance vs l'année précédente à la même date.
- Radar animé des appareils, filtres croisés (clic sur un appareil, une mission ou une carte), cumul vs objectif, projection de fin d'année, analyse automatique.
- `Ctrl+K` ou `/` : palette de recherche (vols, pages, actions, thèmes) · `N` : nouveau vol.
