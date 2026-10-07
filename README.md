# Dragon Quest & Final Fantasy in Itadaki Street Special — Patch FR

Patch de traduction **française** non officiel pour *Dragon Quest & Final Fantasy in Itadaki Street Special* (PlayStation 2, Japon, SLPM-657.97).

## Ce qui est traduit

- Toutes les répliques des personnages (partie normale et mode histoire)
- Les menus, l'interface et les noms (VF officielles quand elles existent)
- Les cartes Chance, les sphères, les fiches des persos et des plateaux
- Les vidéos des règles
- Le clavier de saisie du nom (AZERTY, majuscules/minuscules)

## Ce qu'il te faut

- **Ta propre ISO japonaise** du jeu. Elle n'est pas fournie, et ne la demande pas.
- Un outil pour appliquer le patch, au choix :
  - **[PPF-O-Matic 3](https://www.romhacking.net/utilities/356/)** (Windows) ;
  - **[Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/)**, directement dans le navigateur, rien à installer (accepte aussi les fichiers PPF).

L'ISO doit être la version japonaise d'origine, non modifiée. Pour vérifier : son empreinte doit correspondre à celle du fichier `Itadaki_Street_Special_FR_infos.txt` fourni avec le patch.

## Installation

1. Télécharge `Itadaki_Street_Special_FR_vX.zip` dans les [Releases](../../releases) et décompresse-le : il contient `Itadaki_Street_Special_FR.ppf`.
2. **Fais une copie de ton ISO** : le patch modifie le fichier directement.
3. Ouvre PPF-O-Matic :
   - **ISO/BIN** : ta copie de l'ISO japonaise
   - **Patch** : `Itadaki_Street_Special_FR.ppf`
   - clique sur **Apply**

   Avec Rom Patcher JS : choisis ta copie de l'ISO dans **ROM file**, le `.ppf` dans **Patch file**, puis clique sur **Apply patch** et enregistre l'ISO obtenue.
4. Lance l'ISO patchée dans ton émulateur (PCSX2) ou sur ta console.

## Pack HD pour PCSX2 (optionnel)

Un pack de textures HD remplace l'interface, les cadres, les menus, la mini-carte, les portraits, les cartes Chance et la police par des versions redessinées en haute définition. Il ne fonctionne qu'avec l'émulateur **PCSX2**, avec l'ISO patchée en français.

### Ce qu'il te faut

Dans les [Releases](../../releases) :

- `Itadaki_pack_HD.zip` : les textures HD (ne pas décompresser)
- `Itadaki Options graphiques.exe` : l'outil d'installation et d'options

Mets les deux fichiers **dans le même dossier**, n'importe où sauf dans le dossier de PCSX2.

### Installation

1. Lance `Itadaki Options graphiques.exe`. Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires** puis **Exécuter quand même** (l'outil n'est pas signé).
2. Le pack est trouvé tout seul s'il est à côté de l'exe. Sinon, choisis le fichier `Itadaki_pack_HD.zip`.
3. Vérifie le **dossier des textures de PCSX2**. Il est trouvé automatiquement à l'emplacement habituel ; sinon choisis le dossier `…\PCSX2\textures\SLPM-65797\replacements`. Pour le trouver, dans PCSX2 : *Paramètres > Dossiers* (*Settings > Folders*), ligne *Textures*.
4. Choisis tes options, puis clique sur **Appliquer**.
5. Dans PCSX2, coche *Charger les textures de remplacement* dans *Paramètres > Graphismes*, onglet *Remplacement de textures* (*Settings > Graphics > Texture Replacement > Load Textures*), puis relance le jeu.

### Les options

- **Police** : la police classique du patch (par défaut) ou une autre (Arial, M PLUS Rounded, Verdana, Segoe UI), et la taille des lettres. Les retours à la ligne ne changent pas.
- **Cartes Chance** : illustrations modernes ou cartes d'origine.
- **Interface** : interface HD ou d'origine.
- **Portraits** : visages HD ou d'origine.

Tu peux changer d'avis quand tu veux : relance l'outil, change les options et applique. Le zip du pack n'est jamais modifié.

## Problèmes connus

- Les noms des joueurs viennent de ta sauvegarde : une sauvegarde japonaise garde des noms en japonais.
- Certaines majuscules accentuées s'affichent sans accent (limite de la police du jeu).
- Pack HD : quelques éléments jamais rencontrés pendant la création peuvent rester en définition d'origine.

Pour signaler une faute ou un texte qui déborde, ouvre une *issue* avec une capture d'écran.

## Licence

Traduction française et pack HD © 2026 Thomas (Androsyn), sous licence **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr)** (voir [LICENSE.md](LICENSE.md)) :

- tu peux partager le patch et le pack, et les modifier ;
- en citant l'auteur et en indiquant ce que tu as changé ;
- **pas d'usage commercial** (pas de vente, pas de revente avec le jeu) ;
- les versions modifiées doivent garder la même licence.

Cette licence ne concerne que le travail de traduction et de création. Le jeu, ses personnages, ses images et ses noms restent la propriété de Square Enix.

## Crédits

- Traduction et outils : Thomas (Androsyn)
- Police : M PLUS Rounded 1c (SIL Open Font License)

*Dragon Quest & Final Fantasy in Itadaki Street Special* © Square Enix. Projet de fans gratuit et non officiel, sans lien avec Square Enix. Aucun fichier du jeu n'est distribué ici.
