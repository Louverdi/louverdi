# Louverdi pour Claude

Vos dossiers Louverdi dans votre propre Claude : lire un dossier et ses pièces, et suivre les
méthodes Louverdi — première lecture, pièces manquantes, chronologie, devis, convention
d'honoraires. Les méthodes sont tenues à jour par notre service et arrivent sans rien réinstaller.

Pour les professionnels inscrits sur [Louverdi](https://louverdi.com/). Claude lit, en votre
nom, uniquement ce que vous voyez déjà sur Louverdi. Il ne peut rien envoyer, chiffrer, signer ni
modifier : vous faites tout cela depuis Louverdi.

## Installer (Claude Pro, Max, Team ou Enterprise)

1. Dans Claude : **Personnaliser → Plugins → Ajouter → Ajouter une marketplace**, et collez
   `Louverdi/louverdi`.
2. Installez le plugin **Louverdi**. Activez **Synchroniser automatiquement** pour recevoir les
   mises à jour.
3. Dans l'onglet **Connecteurs** du plugin, connectez **Louverdi** : vous vous connectez à votre
   compte Louverdi et autorisez l'accès. Vous pouvez le retirer à tout moment depuis votre profil
   Louverdi, rubrique « Applications connectées ».

**Cabinets sur Claude Team ou Enterprise.** Un propriétaire de l'organisation peut le rendre
disponible à tous : **Paramètres de l'organisation → Plugins & skills → Ajouter**, avec ce dépôt pour source
(`{"source": "git-subdir", "url": "https://github.com/Louverdi/louverdi.git", "path": "louverdi"}`), puis ajouter
le connecteur Louverdi dans **Paramètres de l'organisation → Connecteurs**.

**Claude Code.** `/plugin marketplace add Louverdi/louverdi` puis `/plugin install louverdi@louverdi`,
et `/mcp` pour vous connecter.

## Ce que lit Claude, et qui le traite

Ce que Claude lit d'un dossier est traité par Anthropic selon votre propre contrat Claude.
Les pièces restent soumises à votre secret professionnel.
