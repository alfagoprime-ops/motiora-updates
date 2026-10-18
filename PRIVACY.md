# Politique de confidentialité — Motiora

*Dernière mise à jour : 18 octobre 2026 · Éditeur : RNY UNIVERSAL LLC · Questions : ouvrez une « issue » sur ce dépôt (onglet Issues).*

Motiora est un logiciel pour Windows qui fabrique des vidéos, des formations, des podcasts et des publicités. **Il fonctionne sur l'ordinateur de l'utilisateur** : l'éditeur n'exploite pas de serveur qui collecte vos fichiers, vos vidéos, vos textes ou vos comptes.

## 1. Ce qui reste sur votre ordinateur
- Vos fichiers, vidéos, images, textes, réglages et journaux sont stockés **localement**.
- Les clés d'accès et jetons (par exemple Pexels, Pixabay, Gemini, Pinterest) sont rangés dans un **coffre chiffré local** (chiffrement Windows DPAPI). Ils ne sont jamais écrits en clair dans un journal et ne sont pas envoyés à l'éditeur.

## 2. Ce qui est envoyé à des services tiers, uniquement quand vous l'utilisez
Motiora envoie des données à un service tiers **seulement lorsque vous lancez une fonction qui en a besoin**, et seulement à celui que vous avez choisi :
- **IA de texte ou de vision** (Gemini, Claude, ChatGPT, etc.) : le texte demandé et, si vous activez « regarder mes médias », de petites images réduites extraites de vos médias. Jamais le fichier entier.
- **Banques d'images et de vidéos libres** (Pexels, Pixabay) : les mots de recherche et la clé d'accès.
- **Pinterest** (API officielle) : voir la section 3.
- **Mises à jour** : Motiora peut consulter ce dépôt public pour savoir si une nouvelle version existe. Aucune donnée personnelle n'est envoyée.

## 3. Pinterest
Quand vous reliez votre compte Pinterest à Motiora :
- Motiora demande à Pinterest l'autorisation de **lister vos tableaux**, **lire vos propres épingles** et **créer des épingles sur vos tableaux**. Il n'accède **jamais** aux épingles, tableaux ou données d'autres personnes.
- Une épingle n'est publiée **qu'après un aperçu et une confirmation explicite de votre part**.
- Le jeton d'accès fourni par Pinterest est conservé dans le coffre chiffré de votre ordinateur. Motiora **ne stocke pas votre mot de passe Pinterest** (la connexion se fait sur le site de Pinterest).
- Motiora ne vend, ne partage et ne transmet aucune donnée Pinterest à qui que ce soit. Elle n'est utilisée que pour exécuter vos demandes (lister, importer, publier).
- Un journal local des publications (date, tableau, titre, identifiant de l'épingle) est tenu sur votre ordinateur, sans aucun secret.
- **Pour retirer l'accès :** dans Motiora, bouton « Déconnecter » (le jeton est supprimé) et, pour révoquer côté Pinterest, Réglages Pinterest > Autorisations / Applications connectées.

## 4. Enfants
Motiora s'adresse à des adultes et à des professionnels ; il n'est pas destiné aux enfants de moins de 13 ans.

## 5. Vos droits
Comme les données sont chez vous, vous gardez le contrôle : vous pouvez les consulter, les modifier ou les supprimer en supprimant les dossiers de Motiora sur votre ordinateur et en vous déconnectant des services reliés. Pour toute question, ouvrez une issue sur ce dépôt.

## 6. Modifications
Cette politique peut évoluer ; la date de mise à jour est indiquée en haut.

---

# Privacy Policy — Motiora (English summary)

Motiora is a Windows desktop application that creates videos, trainings, podcasts and ads. **It runs on the user's computer**; the publisher (RNY UNIVERSAL LLC) operates no server that collects your files, texts or accounts.
- Access keys and tokens (Pexels, Pixabay, AI providers, Pinterest) are stored in an **encrypted local vault** (Windows DPAPI), never in clear text logs, never sent to the publisher.
- Data is sent to third-party services **only when you use a feature that needs them**, and only to the one you chose (AI text/vision providers, stock libraries, Pinterest).
- **Pinterest:** with your consent through Pinterest's official OAuth, Motiora can list your boards, read **your own** pins and create pins on **your** boards. It never accesses other people's pins, boards or data. Every pin is published only after a preview and your explicit confirmation. Your Pinterest password is never stored. Pinterest data is not sold or shared and is used only to carry out your requests. To remove access: use "Disconnect" in Motiora and revoke the app in your Pinterest settings.
- Not intended for children under 13. Questions: open an issue on this repository.
