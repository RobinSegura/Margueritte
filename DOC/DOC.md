# Margueritte
Manuel pour créer le site Wordpress de Marguerite Vrac en moins d'une heure

## Plan en 3 étapes
* Connaître Wordpress
* Choisir un hébergeur
* Créer un compte
* Paramétrer le site

## Connaitre Wordpress
Wordpress est un CMS (système de gestion de contenu) pour créer et gérer un site dynamique. C'est donc ce qu'il vous faut pour afficher un texte de présentation, avoir une page avec quelques commentaires. C'est également l'idéal pour présenter les produits de la boutique en ligne (avec ou sans paiement en ligne, en chèque, ou à la récupération des paniers) et en pouvant tout paramétrer sans l'aide d'un informaticien à chaque fois qu'un produit change.

## Choisir un hébergeur
Aller sur [un comparateur d'hébergeur](https://www.codeur.com/blog/hebergeurs-web-special-wordpress/) et choisir son serveur. Attention de ne pas prendre le moins cher. Les hébergeurs low-cost comme SiteGrownd ont souvent une qualité de service minimale qui peut entraîner des lenteurs à l'affichage.
Conseils:
* [WP Server](https://www.wpserveur.net/) l'hébergeur "officiel"
* [FlyWheel](https://getflywheel.com/) pas cher et pas connu, pourquoi pas
et enfin le meilleur:
* [OVH](https://www.ovh.com/fr/hebergement-web/site/wordpress.xml) (de On-Vous-Heberge) - Français et pas cher

Je vous conseille donc OVH pour héberger votre site. Ils sont basés à Roubaix mais tout se fait en ligne [via ce lien](https://www.ovh.com/fr/order/domain/#/legacy/domain/search?options=~(hosting~'pro2014~module~'wordpress)) pour 5€ par mois

## Créer son compte administrateur
Suivre les étapes dictées par OVH lors de la création du compte (Choisir son nom de domaine (margeritte-vrac.fr par exemple, vérifier le mail, valider le paiement mensuel... )
OVH devrait ensuite vous donner accès à l'administration de votre site sous la forme:
"nom_du_site.com/wp-admin" par exemple [www.marguerite-vrac.fr/wp-admin](www.marguerite-vrac.fr/wp-admin)
aller se connecter à cette adresse avec les identifiants fournis. (appeller votre beau-fils si besoin d'aide)

Ici, commence la découverte de l'espace administrateur de votre site.

## Paramétrer votre site
Wordpress peut faire bien plus que l'affichage d'une boutique. Tout est géré sous forme d'extensions, des modules appelés "plugins". Celui qu'il vous faut pour commencer est "WooComerce". Pour ce faire aller dans le menu latéral: Plugins

### Installer les plugins de sécurité suivants:
* [https://fr.wordpress.org/plugins/hide-my-wp/](https://fr.wordpress.org/plugins/hide-my-wp/)
* [https://fr.wordpress.org/plugins/better-wp-security/](https://fr.wordpress.org/plugins/better-wp-security/)
* [https://fr.wordpress.org/plugins/custom-login-url/](https://fr.wordpress.org/plugins/custom-login-url/)

### Installer le plugin WooCommerce (gratuit)

Comme pour l’installation de n’importe quels plugins WordPress gratuits, vous devez vous rendre dans votre console WordPress admin, cliquer sur Plugins – > Add New (si votre console est en français, « Extensions -> Ajouter une extension »). Écrivez « woocommerce » dans le champ de recherche puis cliquez sur « Installer » ou « Install now » 

![Installer le plugin woocommerce](https://www.wppourlesnuls.com/wp-content/uploads/2018/02/installer-woocommerce.jpg)

Lorsque c’est fait, cliquez ensuite sur le bouton bleu « Activate ». Vous verrez alors le menu de configuration initiale de WooCommerce. Ce processus est très simple à compléter.

### Configurer la boutique

Débutez la configuration en entrant les coordonnées physiques de votre boutique en ligne afin de les afficher sur votre site en ligne. 
Suivre les etapes (ne pas configurer paypal si ce n'est pas nécessaire, idem décocher les methodes d'expédition)

### Création des pages essentielles au fonctionnement de votre boutique en ligne

Une boutique en ligne requiert différentes pages spécifiques partant du début jusqu’à la fin d’une commande en ligne. Nous allons donc créer celles-ci. Dans le module « Pages » de WordPress, créez une à une les pages suivantes en n’ajoutant rien d’autre que le titre à l’intérieur de celles-ci :

Emplacement  | Description
-------------|-----------------------------------------------------------
Boutique | la page d’accueil de votre boutique en ligne
Panier | la page contenant le panier d’achats avec les items ajoutés par le client
Commande | la page dans laquelle votre client ajoutera ses informations de livraisons et de paiement en ligne
Mon compte | (facultatif) une sorte de page de profil pour les clients qui désirent créer un compte sur votre site pour faciliter leurs futures commandes
Conditions générales de vente et d’utilisation | la page contenant les conditions générales de vente et d’utilisation de votre site.

Lorsque ces pages seront créées, vous devez associer celles-ci dans la configuration de WooCommerce. Pour associer la page « Boutique », ouvrez WooCommerce -> Réglages -> Produits.

![page Boutique](https://www.wppourlesnuls.com/wp-content/uploads/2018/04/page-boutique.jpg)
Pour associer les autres pages, ouvrez WooCommerce -> Réglages -> Commande.

![page Commande](https://www.wppourlesnuls.com/wp-content/uploads/2018/04/page-commande-1.jpg)

### Ajouter votre premier produit

![Menu gestion produit](https://www.wppourlesnuls.com/wp-content/uploads/2018/02/onglet-produits.png)

Pour que votre boutique en ligne soit réellement opérationnelle, vous aurez besoin de produits ou d’un service à vendre! Pour ajouter un nouveau produit, allez dans votre console WordPress et cliquez sur « Produits -> Ajouter un produit ». Voici ce que vous verrez à l’écran (chaque numéro dans l’image est décrit plus en détail sous celle-ci) :

![Ajouter un produit](https://www.wppourlesnuls.com/wp-content/uploads/2018/02/ajouter-un-produit.jpg)
1. Le nom de votre produit
2. La description générale de votre produit. Cette section vous permet d’ajouter beaucoup de contenu texte. En utilisant les outils du wyzywyg (what you see is what you get), vous pourrez même ajouter des images, des vidéos, des tableaux, des titres, etc.
3. La portion des données concernant votre produit. Utilisez celle-ci pour indiquer d’abord si votre produit est un produit physique, virtuel ou téléchargeable. S’il s’agit d’un produit physique, ne cochez pas de case. S’il s’agit d’un service, celui-ci est considéré comme un produit virtuel. Voici les autres portions de cette section centrale :
* Général : Qui vous sert à définir le prix du produit et ses taxes
* Inventaire : Pour gérer votre inventaire (si nécessaire)
* Expédition : Pour définir les dimensions, le poids et le prix de livraison du produit
* Produits liés : Pour définir des produits similaires du genre : « Les clients qui ont acheté ce produit ont aussi acheté ceux-ci … »
* Attributs : Pour ajouter des attributs du genre : grandeur, couleur, matériel…
* Avancés : Contenant les champs « Note d’achat », « Ordre du menu » et « Activer les avis »
4. Description courte du produit : Ce texte sera affiché sous le titre du produit dans la page (single-product) du produit.
5. Catégories de produit : Pour regrouper les produits d’une même catégorie (ex: catégorie « chandails » sous la catégorie « hommes » )
6. Étiquettes produit :  Une autre façon de regrouper vos produits (ex: des marques en particulier)
7. Image produit : L’image principale de votre produit (qui sera aussi utilisée en miniature dans vos pages de catégories ou sur la page Boutique)
8. Galerie produit : Une galerie contenant différentes images de votre produit

### Dernière étape: Choisir le visuel de votre boutique en ligne
WooCommerce et votre thème actuel

Par défaut, WooCommerce est compatible avec tous les thèmes WordPress. Une bonne nouvelle si vous avez un site au visuel personnalisé, car vous pourrez conserver celui-ci. La moins bonne nouvelle est que ce ne sont pas tous les thèmes qui afficheront les informations de votre boutique avec les visuels désirés selon vos goûts et préférences. Il se peut que votre intégrateur ou programmeur ait à faire quelques retouches sur celui-ci.

Aussi, si vous avez un thème qui a été créé de A à Z par un programmeur, il se peut que celui-ci n’est pas programmé de base (ce qui serait normal selon le budget que vous lui aviez alloué au départ du mandat) pour être compatible avec WooCommerce. Dans ce cas-ci, vous aurez à payer ce même programmeur ou une nouvelle personne pour compléter votre thème en lien avec votre nouveau projet de e-commerce.

Si changer le visuel de votre site n’est pas un problème, il existe de nombreux thèmes premium conçus et optimisés spécialement pour WooCommerce. Ainsi, toutes les pages de catégories, de produits et du processus de paiement en ligne seront toutes déjà programmées et designées pour une boutique impeccable.

![themeforest woocommerce](https://www.wppourlesnuls.com/wp-content/uploads/2018/04/themeforest-woocommerce-themes.jpg)

L’équipe de WooCommerce a également créé un thème de base appelé Storefront qui peut être une alternative à payer un thème premium. Voici la vidéo de présentation du thème. Il s’agit d’une alternative gratuite, mais qui comprend plusieurs limites visuelles.

    * Pour votre info, les thèmes de ThemeForest sont programmés dans le même sens que celui de Storefront pour assurer une compatibilité maximale avec WooCommerce.

Peu importe si vous décidez de conserver votre thème actuel ou de modifier celui-ci pour un thème WooCommerce, la prochaine étape consiste justement à vérifier que chacune des pages de votre boutique en ligne fonctionne adéquatement.
