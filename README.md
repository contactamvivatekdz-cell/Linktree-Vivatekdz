# Vivatek DZ — page Linktree

Page de liens publique pour **Vivatek DZ** (*Choose Distinction. Live Quality. — اختر التميز وعش الجودة*), en français et en arabe, optimisée pour téléphone et ordinateur.

## Ce que contient la page
- **Accueil** : logo officiel, message de bienvenue et de remerciement, boutons *Découvrir la boutique* et *Écrire sur WhatsApp*, livraison 58 wilayas.
- **À propos** : l'esprit de la marque, en trois idées (Choisir la distinction, Vivre la qualité, Chez vous, partout).
- **Nos réseaux** : boutique en ligne (mise en avant), Instagram, Facebook, TikTok.
- **Contact** : WhatsApp (message pré-rempli), message Instagram et e-mail.
- Un bouton WhatsApp flottant qui apparaît après l'accueil.

## À vérifier avant de publier
1. **Image de partage** : dans `index.html`, remplacez `content="assets/og-image.jpg"` (balise `og:image`) par l'adresse complète une fois le site publié, par exemple `https://VOTRE-NOM.github.io/vivatek-dz/assets/og-image.jpg`. Sans cela, l'aperçu du lien sur les réseaux peut ne pas afficher l'image.
2. **Liens déjà configurés**
   - Boutique : `https://vivatekdzshop.set.shop/store/3zicxun/produits`
   - WhatsApp : `0782860904` (lien `https://wa.me/213782860904`, avec un message d'accueil pré-rempli)
   - Instagram : `https://www.instagram.com/vivatek_dz/` (message : `https://ig.me/m/vivatek_dz`)
   - TikTok : `https://www.tiktok.com/@vivatek_dz`
   - Facebook : `https://www.facebook.com/profile.php?id=61594979983985`
   - E-mail : `contact.amvivatek.dz@gmail.com`

## Tester en local
Ouvrez `index.html` dans votre navigateur. Une connexion Internet est utile pour charger les polices Google (Cormorant Garamond, Montserrat, Cairo). Sans connexion, des polices de secours sont utilisées.

## Publier gratuitement avec GitHub Pages
1. Connectez-vous à https://github.com/new
2. Créez un dépôt nommé `vivatek-dz`, en **Public**.
3. Cliquez sur **Add file → Upload files**.
4. Téléversez `index.html`, `style.css`, `README.md` et le dossier `assets` (avec tous ses fichiers).
5. Cliquez sur **Commit changes**.
6. Ouvrez **Settings → Pages**.
7. Sous **Build and deployment**, choisissez **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`, et cliquez sur **Save**.
8. Après quelques minutes, l'adresse apparaît dans Pages, sous la forme `https://VOTRE-NOM.github.io/vivatek-dz/`.

## Modifier la page
- Textes et liens : `index.html`
- Couleurs et mise en page : `style.css` (les couleurs sont regroupées au début, dans `:root`)
- Images : dossier `assets` (logo officiel recadré, icônes, image de partage)

### Couleurs de l'identité (mesurées sur le logo)
| Rôle | Valeur |
|---|---|
| Bleu principal | `#122138` |
| Bleu profond | `#0a1524` |
| Bleu clair | `#283952` |
| Or | `#e2ae57` |
| Or clair | `#f6cc77` |
| Or foncé | `#c28a37` |

Cette page est statique : elle ne collecte aucune donnée et ne demande ni serveur ni base de données.
