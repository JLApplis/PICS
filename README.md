# 🌿 PICS
### Pilotage Immobilier Copropriété Syndic

**Un outil libre et gratuit pour les conseils syndicaux bénévoles.** Suivez vos réunions, actions, prestataires, documents — et contrôlez les comptes de votre syndic.

**[▶️ Essayer la démo en ligne](https://JLApplis.github.io/PICS/pics_demo.html)** • **[⬇️ Télécharger PICS](https://github.com/JLApplis/PICS/releases/latest/download/pics.html)**

*Aucune installation • Aucun compte • Aucun serveur • Vos données restent chez vous*

![Licence](https://img.shields.io/badge/licence-GPL_v3-blue) ![Fichier unique](https://img.shields.io/badge/fichier-HTML_unique-green) ![Sans serveur](https://img.shields.io/badge/serveur-aucun-orange)

---

## Ce que PICS résout

Vous êtes bénévole dans un conseil syndical. Entre les réunions, les devis, les relances de prestataires, les non-conformités à suivre et les comptes du syndic à vérifier, l'information se disperse dans des mails, des tableurs et des dossiers papier.

PICS rassemble tout dans **un seul fichier** qui s'ouvre dans votre navigateur. Vous le téléchargez, vous double-cliquez, vous travaillez. Rien à installer, rien à configurer, rien qui parte sur internet.

## L'argument n°1 : le contrôle de gestion du syndic

La plupart des outils de copropriété s'arrêtent au suivi des tâches. PICS va plus loin : il **rapproche automatiquement les comptes fournis par votre syndic** avec ce que vous avez suivi de votre côté, à partir des fichiers CSV que le syndic exporte.

Trois outils de rapprochement intégrés :

- **💶 Rapprocher les dépenses** — croise les factures du syndic avec vos actions suivies. Repère les actions sans facture et les factures sans action.
- **📊 Suivi budgétaire** — compare budget voté et dépenses réelles : dépassements, postes en tension, charges hors budget.
- **📑 Rapprocher les contrats** — vérifie que les montants facturés correspondent aux contrats en cours, signale les écarts et les factures sans contrat rattaché.

Vous n'avez rien à saisir en double : vous chargez le CSV du syndic, PICS fait le rapprochement et vous montre où regarder.

## Les 6 modules

| Module | À quoi ça sert |
| --- | --- |
| 📊 **Tableau de bord** | Vue d'ensemble, alertes, échéances |
| 📅 **Réunions** | AG, conseils syndicaux, entretiens, comptes rendus |
| 🎯 **Actions** | Tâches et travaux, cycle devis / ordre de service / facture |
| 🔧 **Non-conformités** | Problèmes et litiges, avec fils de mails |
| 🏢 **Prestataires** | Entreprises, contacts, contrats |
| 📁 **Documents** | Contrats, factures, liens vers vos fichiers locaux |

Les modules avancés (Non-conformités, Documents) sont masqués au premier lancement pour rester simple : on les affiche via **⋯ Autres modules** quand on en a besoin.

## Suivre les travaux jusqu'à la facture

Un chantier peut être terminé sans que la facture soit arrivée. PICS distingue donc deux étapes :

- **Date réalisée** — les travaux sont faits
- **Date terminée** — la facture est arrivée et rapprochée du CSV du syndic

Le rapprochement des dépenses fait ressortir les **actions réalisées dont la facture manque encore** : c'est exactement la liste à transmettre à votre syndic. Un bouton **📋 Copier la sélection** produit un tableau prêt à coller dans un mail.

## Vos données restent chez vous

- PICS est un **fichier HTML autonome** : aucune installation, aucun serveur, aucun compte.
- Il ne se connecte **jamais** à internet et ne contient aucun code de suivi.
- Vos données sont enregistrées **uniquement dans la mémoire de votre navigateur**, sur votre ordinateur.
- Sauvegarde par **export JSON horodaté** : un simple fichier que vous gardez où vous voulez.

> ⚠️ **Important — la sauvegarde vous appartient.** Vider le cache de votre navigateur, changer d'ordinateur ou de navigateur efface les données enregistrées. **Votre seule sauvegarde est le fichier JSON que vous exportez vous-même** (**💾 Données → ⬇️ Exporter**). Exportez régulièrement et conservez plusieurs exports successifs, à l'abri.

PICS vous y aide : rappel périodique, avertissement si vous fermez l'application avec des modifications non exportées, signalement immédiat si le navigateur refuse d'enregistrer. Ces alertes ne remplacent pas vos propres sauvegardes.

## Démarrer en 3 étapes

1. **[Téléchargez `pics.html`](https://github.com/JLApplis/PICS/releases/latest/download/pics.html)** (bouton *Download* de la dernière version).
2. **Double-cliquez** sur le fichier : il s'ouvre dans votre navigateur (Chrome, Edge, Firefox, Safari).
3. **Commencez à saisir.** Le guide intégré (bouton ❓) vous accompagne.

> 💡 Pour garder le fichier à portée de main, placez-le dans un dossier dédié et créez un raccourci.

## Lier vos documents (contrats, devis, factures)

PICS n'enregistre pas vos fichiers : il conserve un **lien** vers leur emplacement sur votre ordinateur. Pour que ces liens restent valables dans le temps, un peu de méthode s'impose.

1. À côté de `pics.html`, créez un dossier dédié — par exemple `DOCUMENTS` — et rangez-y vos contrats, devis et factures.
2. Dans une fiche PICS, cliquez sur **＋ Ajouter un lien**. Pour renseigner le chemin du fichier : dans l'explorateur Windows, faites un **clic droit sur le fichier → Copier en tant que chemin d'accès**, puis collez ce chemin dans le champ.

> ⚠️ **Point essentiel : une fois les liens créés, ne déplacez plus ce dossier et ne le renommez pas.** Chaque lien pointe vers un emplacement précis ; si le dossier `DOCUMENTS` change de nom ou de place dans l'arborescence, **tous les liens deviennent invalides**. Gardez `pics.html` et son dossier `DOCUMENTS` au même endroit — si vous devez tout déplacer, déplacez-les d'un seul bloc, ensemble.

> 💡 Selon votre navigateur et ses réglages de sécurité, l'ouverture d'un fichier local depuis un lien peut être bloquée. Dans ce cas, copiez le chemin affiché et collez-le dans la barre d'adresse d'un nouvel onglet.

## Compatibilité

Fonctionne sur **Chrome, Edge, Firefox, Safari** — PC, Mac ou tablette. Aucune connexion internet requise après le téléchargement.

## Licence

PICS est distribué sous licence **[GPL v3](LICENSE.txt)**. Vous êtes libre de l'utiliser, l'étudier, le partager et le modifier, à condition de conserver la même licence pour vos versions dérivées.

Deux points méritent d'être connus :

- **Toute version modifiée doit être signalée comme telle**, avec sa date (article 5(a) de la licence). C'est ce qui permet de ne pas attribuer à l'auteur d'origine les défauts d'une version qu'il n'a pas écrite.
- **Le code est libre, les noms ne le sont pas.** « PICS » et « JLApplis » identifient l'origine du logiciel : une version modifiée se distribue sous un nom différent. Les détails figurent dans [TRADEMARK.md](TRADEMARK.md).

## Garantie et responsabilité

PICS est développé **bénévolement** et mis à disposition **gratuitement**, en dehors de toute activité professionnelle. Il est fourni **en l'état, sans garantie d'aucune sorte**, conformément aux articles 15 et 16 de la GPL v3.

**Vos données ne transitent par aucun serveur et ne sont accessibles qu'à vous.** Elles sont enregistrées par votre navigateur, sur votre ordinateur. L'auteur n'y a aucun accès et ne peut donc en assurer ni la conservation ni la restauration.

**La sauvegarde relève de l'utilisateur.** Vider le cache du navigateur, changer d'ordinateur ou de navigateur, ou utiliser la navigation privée fait disparaître les données enregistrées. La seule sauvegarde est le fichier JSON que vous produisez vous-même (**💾 Données → ⬇️ Exporter**) et que vous conservez à l'abri. Exportez régulièrement, et conservez plusieurs exports successifs.

PICS vous y aide — rappel périodique, alerte à la fermeture si des modifications n'ont pas été exportées, signalement immédiat si le navigateur refuse d'enregistrer — mais ces avertissements ne remplacent pas vos propres sauvegardes.

En utilisant PICS, vous reconnaissez avoir pris connaissance de ces informations et assumer la responsabilité de la sauvegarde de vos données.

## Versions

La version en cours est **PICS 3.2**. Le numéro est affiché dans l'en-tête de l'application et dans le titre de l'onglet : une simple capture d'écran suffit donc à identifier la version utilisée.

**Ce dépôt est la seule source officielle de PICS.** Une copie obtenue ailleurs peut être modifiée, périmée, ou les deux — comparez-la à la [dernière version publiée ici](https://github.com/JLApplis/PICS/releases/latest).

## Contact

Développé bénévolement par **Jean-Luc ALVAREZ** — **<contact@jlapplis.fr>**

Un retour, une idée, un bug ? Ouvrez une [*issue*](https://github.com/JLApplis/PICS/issues) ou écrivez-moi.

---

*PICS est gratuit et le restera. Si l'outil vous rend service, faites-le connaître autour de vous.*
