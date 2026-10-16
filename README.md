# Louverdi pour Claude

Vos dossiers Louverdi dans votre propre Claude : lire un dossier et ses pièces, et suivre les
méthodes Louverdi — première lecture, pièces manquantes, chronologie, devis, convention
d'honoraires. Les méthodes sont tenues à jour par notre service et arrivent sans rien réinstaller.

**Une seule commande : `/louverdi`**, suivie de ce que vous voulez — « /louverdi envoie ce
contrat », « /louverdi où en est EDV-2026-0148 », « /louverdi chronologie EDV-2026-0148 ».

**Entreprises et particuliers** : joignez un contrat ou décrivez votre situation, tapez
`/louverdi`, et le dossier nous arrive. Si vous avez enregistré vos réponses de consentement sur
Louverdi, il part directement ; sinon votre IA prépare un brouillon que vous terminez sur Louverdi.
Votre IA ne nous transmet pas le fichier d'origine, seulement ce qu'elle en a lu : joignez le
document sur Louverdi. Elle ne peut ni accepter un devis, ni payer, ni signer.

Pour les professionnels inscrits sur [Louverdi](https://louverdi.com/). Claude lit, en votre
nom, uniquement ce que vous voyez déjà sur Louverdi. Il ne peut rien envoyer, chiffrer, signer ni
modifier : vous faites tout cela depuis Louverdi.

## Installer (Claude Pro, Max, Team ou Enterprise)

0. Sur Louverdi, ouvrez votre profil, rubrique « Votre IA », et cliquez sur **Activer l'accès IA**.
   Sans cela, la connexion est refusée. Vous pouvez le couper au même endroit, à tout moment.
1. Dans Claude : **Personnaliser → Plugins → Ajouter → Ajouter une marketplace**, choisissez
   **Ajouter depuis un dépôt** (pas « Parcourir les sources Anthropic » : Louverdi n'est pas dans
   cette liste), et collez `Louverdi/claude-plugins`.
2. Installez le plugin **Louverdi**. Activez **Synchroniser automatiquement** pour recevoir les
   mises à jour.
3. Dans l'onglet **Connecteurs** du plugin, connectez **Louverdi** : vous vous connectez à votre
   compte Louverdi et autorisez l'accès. Vous pouvez le retirer à tout moment depuis votre profil
   Louverdi, rubrique « Votre IA ».

**Cabinets sur Claude Team ou Enterprise.** Un propriétaire de l'organisation peut le rendre
disponible à tous : **Paramètres de l'organisation → Plugins & skills → Ajouter**, depuis une
marketplace privée du cabinet qui référence ce dépôt
(`{"source": "git-subdir", "url": "https://github.com/Louverdi/claude-plugins.git", "path": "louverdi"}`), puis ajouter
le connecteur Louverdi dans **Paramètres de l'organisation → Connecteurs**.

**Claude Code.** `/plugin marketplace add Louverdi/claude-plugins` puis `/plugin install louverdi@louverdi`,
et `/mcp` pour vous connecter.

## Ce que lit Claude, et qui le traite

Ce que Claude lit d'un dossier est traité par Anthropic selon votre propre contrat Claude.
Les pièces restent soumises à votre secret professionnel.
