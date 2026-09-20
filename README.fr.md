# Lumen — Desktop Orb

[![Website](https://img.shields.io/badge/Website-lumen--orb-38bdf8)](https://alex-stark-industries.github.io/Lumen-Desktop-Orb/)
[![Download](https://img.shields.io/badge/Download-Latest%20Release-38bdf8?logo=github)](../../releases/latest)
[![License](https://img.shields.io/badge/License-Free%20to%20use-2ea44f)](LICENSE)
[![Platform](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?logo=windows)](../../releases/latest)

**Une petite sphère vocale qui vit sur votre bureau.**
Clic droit pour un menu de commandes rapides — l'heure, l'état du système,
la météo, une recherche web, ouvrir n'importe quelle application par son nom —
chacune avec une réponse **instantanée** et **prononcée à voix haute** par une vraie voix.

> **Aucun compte. Aucun abonnement. Aucun modèle de langage. Aucun cloud.**
> Juste une petite lumière flottante qui répond vite et reste discrète.

---

### Points forts

- 🔵 **Une sphère de particules vivante** — un orbe lumineux et doux qui dérive au repos et ondule comme un liquide en parlant.
- ⚡ **Réponses instantanées** — chaque commande rapide est une recherche ou une action déterministe, pas un modèle qui « réfléchit ». Rien à attendre.
- 🎙️ **Une vraie voix parlée** — une véritable voix neuronale locale, pas une synthèse robotique du système.
- 🖱️ **Clic droit pour tout** — un menu personnalisé et épuré constitue toute l'interface. Aucune fenêtre à gérer, aucun réglage à chercher.
- 🌦️ **Météo, recherche web, ouvrir n'importe quelle app par son nom** — les quelques commandes qui ont besoin d'un mot ou deux le demandent directement.
- 🪶 **Petit et discret** — aucun modèle de langage, aucun téléchargement de plusieurs gigaoctets, aucun service en arrière-plan. Il ne télécharge que la voix elle-même, une seule fois.

---

### Captures d'écran

<table>
<tr>
<td width="50%">

**L'orbe** — au repos, dérivant tranquillement sur le bureau.
<img src="docs/screenshots/orb.png" alt="Lumen desktop orb" width="100%">

</td>
<td width="50%">

**Menu du clic droit** — chaque commande à portée d'un clic.
<img src="docs/screenshots/menu.png" alt="Lumen right-click command menu" width="100%">

</td>
</tr>
</table>

---

### Téléchargement et installation

1. Ouvrez la page des [**Releases**](../../releases/latest) et téléchargez
   `Lumen Setup <version>.exe`.
2. Lancez-le. L'installateur est **par utilisateur** — **aucun droit administrateur requis**.
3. Lumen apparaît sous forme d'une petite sphère lumineuse en bas à droite de l'écran.

> **Premier lancement :** l'installateur n'est pas signé numériquement, donc Windows SmartScreen
> peut afficher *« Windows a protégé votre PC »*. Cliquez sur **Informations complémentaires → Exécuter quand même**.
> C'est normal pour une application gratuite et indépendante.

Nouveau ici ? Le [**Guide de bienvenue**](WELCOME.md) accompagne pas à pas
l'installation et la première commande, sans rien présumer.

**Aucune autre configuration nécessaire** — contrairement aux assistants IA plus lourds,
Lumen n'a aucun modèle à télécharger ou installer au préalable. La toute première réponse parlée
télécharge un petit modèle vocal (quelques centaines de Mo, une seule fois) ; tout le reste
ensuite est instantané et entièrement hors ligne.

---

### Documentation

| Document | Contenu |
|---|---|
| [Guide de bienvenue](WELCOME.md) | Pour débutants, étape par étape : installation, lancement, première commande |
| [Guide des commandes](GUIDE.md) | Chaque commande, ce qu'elle fait et comment l'utiliser |
| [Confidentialité](PRIVACY.md) | Exactement ce qui touche (et ne touche pas) le réseau |
| [Licence](LICENSE) | Gratuite — conditions complètes |
| [Mentions tierces](THIRD-PARTY-NOTICES.md) | Composants open source utilisés par Lumen |

---

### Configuration requise

| | Minimum |
|---|---|
| **Système** | Windows 10 / 11, 64 bits |
| **RAM** | 4 Go |
| **Espace libre** | ~500 Mo (application + modèle vocal) |
| **Internet** | Uniquement pour le téléchargement unique du modèle vocal et les commandes Météo / Recherche web |

Tout le reste — l'horloge, l'état du système, l'ouverture d'applications, le menu lui-même —
fonctionne entièrement hors ligne.

---

### Confidentialité en bref

- **Aucun compte, aucune clé API, aucune télémétrie, aucune analyse.**
- **Aucun modèle de langage ne tourne jamais** — chaque commande est une routine
  petite et fixe, pas une IA qui décide quoi faire.
- La voix (synthèse vocale) tourne **sur l'appareil**, après un téléchargement unique.
- Lumen **se met à jour toute seule** — elle vérifie GitHub discrètement en arrière-plan
  et installe les nouvelles versions d'elle-même, pour que vous n'ayez jamais à revenir ici
  chercher un correctif.
- Le seul usage du réseau, toujours : ce téléchargement vocal unique, la vérification
  de mise à jour, et les deux commandes explicitement tournées vers le monde extérieur
  (**Météo**, **Recherche web**).

Détails complets : [PRIVACY.md](PRIVACY.md).

---

### Licence

Gratuite — mais c'est une licence, pas un logiciel open source : aucune redistribution,
aucune revente, aucune modification. Voir les conditions complètes dans [LICENSE](LICENSE).

*Non affiliée, non sponsorisée et non associée à un film, un jeu,
une franchise ou une marque quelconque. « Lumen » signifie simplement « lumière » en latin.*

---

Lire dans une autre langue : [English](README.md) · [Italiano](README.it.md) · [Español](README.es.md) · [Deutsch](README.de.md) · [हिन्दी](README.hi.md)
