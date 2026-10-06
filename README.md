# DoFix

DoFix est un petit programme Windows pour jouer à Dofus en multicompte : il range tes fenêtres en équipes, te fait passer de l'une à l'autre en une touche, reproduit un clic sur toute l'équipe et colle automatiquement ce que Ganymede copie.

Un seul programme, rien d'autre à installer. Windows 10 ou 11, 64 bits.

> DoFix est un projet personnel, sans lien avec Ankama. Lis la section [À savoir](#à-savoir) avant de l'utiliser.

## Installation

1. Ouvre la page ([Releases]([#https://github.com/BeAzarym/DoFix-realeases/releases)).
2. Télécharge `DoFix-Setup-x.y.z.exe` et lance-le.
3. Windows peut afficher « Windows a protégé votre ordinateur » : clique sur **Informations complémentaires**, puis **Exécuter quand même**. Le programme n'est pas signé, c'est la seule raison de cet avertissement.

L'installation se fait dans ton profil, sans droits administrateur. DoFix apparaît dans le menu Démarrer.

## Premiers pas

1. Lance tes personnages Dofus, puis DoFix.
2. **Sélection** : coche les personnages à gérer et clique sur **Valider**.
3. **Dashboard** : glisse les cartes pour définir l'ordre de l'équipe. Cet ordre sert partout : navigation, grille, barre des tâches.
4. Ferme la fenêtre : DoFix reste actif près de l'horloge. `Ctrl + Alt + M` rouvre le dashboard.

## Fonctions

### Équipes
- Jusqu'à 8 personnages par équipe, sur une ligne. Glisser-déposer pour changer l'ordre.
- **Chef d'équipe** (clic droit sur une carte) : c'est lui qui reçoit le collage automatique et vers qui DoFix revient après un clic reproduit.
- **GROUPER** : envoie `/invite` chez le chef pour chaque autre personnage de l'équipe.
- **Fenêtres inactives** : la croix rouge d'une carte sort le personnage de l'équipe sans fermer sa fenêtre. Le « + Ajouter » le remet dans l'équipe.
- **Kick** (clic droit) : ferme la fenêtre du personnage.
- Glisser une carte sous les équipes crée une nouvelle équipe.

### Équipes sauvegardées
- **Enregistrer l'équipe active** garde les personnages, leur ordre et le chef.
- **Charger** reforme l'équipe avec les personnages présents. Les autres passent en fenêtres inactives.

### Navigation et clics
- Fenêtre suivante / précédente, accès direct aux fenêtres 1 à 8.
- **Cercle des fenêtres** : maintenir le clic molette, choisir un personnage par son pseudo.
- **Clic reproduit** : `Ctrl + Alt + clic` rejoue le clic au même endroit dans chaque fenêtre de l'équipe.
- **Grille** : `Ctrl + Alt + G` range les fenêtres en grille ; une deuxième fois, il les remet toutes en grand.

### Collage automatique
Quand Ganymede copie quelque chose, DoFix passe sur la fenêtre du chef, colle et valide.

### Barre des tâches
Les fenêtres de l'équipe active sont rangées dans l'ordre de l'équipe dans la barre Windows, avant les fenêtres inactives.

## Raccourcis par défaut

Tous s'utilisent avec **Ctrl gauche + Alt gauche**. AltGr reste libre. Ils se modifient ou se suppriment un par un dans **Keybind**.

| Raccourci | Action |
|---|---|
| `Ctrl + Alt + M` | Ouvrir le dashboard |
| `Ctrl + Alt + ←` / `→` | Fenêtre précédente / suivante |
| `Ctrl + Alt + Molette` | Défiler entre les fenêtres |
| `Ctrl + Alt + 1` … `8` | Aller à la fenêtre n° |
| `Ctrl + Alt + ↑` / `↓` | Équipe précédente / suivante |
| `Ctrl + Alt + G` | Grille / fenêtres en grand |
| `Ctrl + Alt + clic` | Clic reproduit sur toute l'équipe |
| `Ctrl + Alt + P` | Mode normal / discret |
| `Ctrl + Alt + Page haut` / `Page bas` | Clics plus rapides / plus lents |
| `Ctrl + Alt + V` | Collage automatique oui / non |
| `Ctrl + Alt + H` | Fenêtre des raccourcis |
| `Ctrl + Alt + Q` | Quitter DoFix |
| Boutons latéraux de la souris | Fenêtre précédente / suivante |
| Maintenir le clic molette | Cercle des fenêtres |

## Mises à jour

Au démarrage, DoFix regarde si une nouvelle version est publiée ici. Si oui, un bouton **Mise à jour** apparaît en haut du dashboard : un clic télécharge et lance l'installeur. Tes réglages et tes équipes sauvegardées sont conservés.

La vérification se coupe dans **Paramètres → Application**. Tu peux aussi installer une nouvelle version à la main, par-dessus l'ancienne.

## Désinstallation

**Paramètres Windows → Applications → Applications installées → DoFix → Désinstaller.** Le désinstalleur demande s'il doit aussi supprimer tes réglages et tes équipes sauvegardées.

## À savoir

- **Règles du jeu** : DoFix n'est ni fourni ni approuvé par Ankama. Les outils qui envoient une action sur plusieurs fenêtres à la fois peuvent être contraires aux règles de Dofus. Vérifie les règles en vigueur et utilise le clic reproduit à tes risques.
- **Antivirus** : DoFix écoute le clavier et la souris pour ses raccourcis et simule des clics. Certains antivirus peuvent le signaler à tort.
- **Données** : tout reste sur ton PC, dans `DoFix.ini` à côté du programme. La seule connexion réseau est la vérification de mise à jour auprès de GitHub.
