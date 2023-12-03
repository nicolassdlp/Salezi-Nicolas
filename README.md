# FR - SALEZI 

## INTRODUCTION

**Bonjour, ceci est le guide d’utilisation du projet Salezi. Ce projet à été réalisé pour la FNAC, dans lequel on doit développer une API robuste et sécurisée pour la gestion des stocks et des ventes des partenaires commerciaux tel que France-Billet,... . Pour réaliser ce projet nous allons utiliser Strapi avec une base de données SQLite. Le but est de permettre aux différents utilisateurs (Super Admin, Fnac Manager, Vendeur) de gérer facilement et efficacement leur produits et leurs ventes ainsi que la gestion des stocks. Ce projet va faciliter la collaboration entre la FNAC et ses partenaires. Pour aller plus loins j'ai crée un site web qui permet de faire office de front-end de l'api.**

Pour faire ce projet j'ai commencé par installé Strapi, j'ai ensuite crée une base de donnée SQLite. Ensuite j'ai crée un dépot GIT afin de pouvoir accéder mon projet à tout moment. Après avoir fait tout ça je me suis rendu sur l'interface administrateur de Strapi et j'ai configurer tout le back-end (les collections, les roles, les users, ainsi que les Token,...). Tout en m'assurant de faire en sorte que le back-end soit sécurisé. Puis pour finir je suis allé dans postman afin de teste toutes les routes de mon API et j'ai crée un dossier pour vous prêt à l'emploie pour Postman. Puis ensuite je me suis mis à coder un front-end sécurisé pour cette API.

## DÉMARRAGE

1. Ouvrez le dossier que je vous ai fourni dans vs code. 
2. Ouvrez le terminal vs code.
3. Ecrivez cette commande "npm run develop" (assurez vous de bien être dans my-project).
4. Maintenant cliquer sur le lien admin que l'on vous donne dans le terminal.
5. Connectez-vous avec les identifiants SuperAdmin fourni ci-dessous.
6. Ouvrez un autre terminal et écrivez cette commande "npm start" (assurez vous de bien être dans salezi-react). 
7. Normalement une page web ce démarre automatiquement.
8. Parfait, maintenant lancé le fichier Postman que je vous ai fourni.
9. C'est tout bon, vous êtes prêt à l'utilisation.

## LES IDENTIFIANTS POUR POSTMAN

### IDENTIFIANT SUPER ADMIN
    email : superadmin@fnac.com
    password : Password1
    token : "377d6d2964ddcf1c0c2956d6aa45494aa15902a6f351931fce2475e46fa82497089385d39bdda764ef02acaf116d3fb9c9807cfee7786a1cfa459ce919e57c79592cb8deb29ee75fe45ad6f65b6b5a529fef63d3690a96410f83a7d50ffa3a56cdd8c79e808d7866692b914d747b4db78dcb48b47ec4ade13cf4466cb19bacdd

### IDENTIFIANT FNAC MANAGER
    email : clara38@manager.com
    password : Password1
    token : 0062b212dac50375eb48d922629a774695f8a062f790773abc5cdd6c17bb5869e0e8080e5c3d4c8d111e5ef8fc37a49f49f51fc17c2bc258aca5ed8329668b96451547f25a8b6e69ecb370ed9b86f04756e661a61a5588904ac2feed67f0d1502f2366ab55c069a0ac264e54a19a833f83b1f254f562c3198ef3f249ceadb6a6

### IDENTIFIANT VENDEUR GENERAL
    email : marcusdelavega@vendeur.com
    password : Password1
    token : 8ed9054c3457e3eb24d2f532e05a1f2a05fa45dc6cdfca85aea8777d9c789c16209d4d5e0125e1728f26ae34a03b12f223d939dfd8c330b97e1483b5ed7d2052f31bd03753c8410ae02d6f1017a5523a2414d0c8e5adf53b5c15b46f49474be3f6479f557a3b50cac8ab7e2ad5d9cbf5e54bd008318abe9c2edff6488b7e9f3c

### IDENTIFIANT VENDEUR FRANCE-BILLET
    email : elodieetoile@vendeur.com
    password : Password1
    token : 308704a5f1164bd872affdaaa66b55da6fe79661189b968b3cdf4b39893819a9c21e5d7cf6117421ed1e4e2b3d2f030a346eac8f2d625950dd5dc504859178e810e341cb6a5e48f51c5c08440662a2669bf0763da199db2c2f886fadce058084dca107cfbd496eccfe7dbcf0e620f589120f5e9c77afedd85065f6d4899cf908

### IDENTIFIANT VENDEUR MISTER GOOD DEAL
    email : theophiletrendy@vendeur.com
    password : Password1
    token : 2117079a1afec8dae2960487a19884cffe4e2063e2d53f9bf85d76b98220539ff88386c9280a9ef3d75c93dff8e8125312c1fd767bdfde1a13f32e35803cf7e7628dcd5c152f602a0f3b939e0203ec052b89e8b976aa4d89211d7e6249b4f2869afebe031fa8ec9ecf46050cc547cd3250b32f1bb8faa3a3db2aa3bdad6ce5bf

### IDENTIFIANT VENDEUR WEFIX
    email : maximystique@vendeur.com
    password : Password1
    token : bcbba8eaa37bec5a494f59ca69a77e9be3ab4a6ad8c87f99289de99e33db1f996189ed36097a325152fce0a2530b9b46ed86d41bda19d79b826cc848247eb09f4920c6a7ac70531a1d8d4e78c318adeb5b957c3575c594823e353a174cad730ec1c72424e3c77cd21bc8f0ac41ab3fddabd25668e4f56ea982be5c30e1cb70a3

### IDENTIFIANT VENDEUR BILLET-REDUC
    email : leandrelumiere@vendeur.com
    password : Password1
    token : d32a787c79b934ae0c36cf29887f1620b8186d0d6ab5eef9792925788c736648ed1110a08d98f793a980c53cb14c664a16332db6e34a6df4bfeda5b83f96066ab4055288e86a71e168fb5f8013b93132f0fc24252b594e015134e35eeba9faa13a7ad89d7abfec51d52df1a3da43fd9cf612bf7ee4fc3aa09e90e8bab09da823

### IDENTIFIANT VENDEUR VANDEN BORRE
    email : aurelieartive@vendeur.com
    password : Password1
    token : 47a72efae4b4946c13df2e064e9512872679d91b629a543e56094396e7502dc6ffe71e4249ff6c368ea8186884cdb6e82fd3601c4b9188312fab813000daf1057661e70ce9499e7ac7ad50a39bc7af3b125ce27fe917eda69d0d0aeef47667838ce5ac9786f9c8a3ca9c929abcfbda3b036738dfecb523f39ee38e3a0cc05182

### IDENTIFIANT VENDEUR NATURE & DÉOUVERTE
    email : alexisciel@vendeur.com
    password : Password1
    token : 3e1031e0a5c0f0089271b2913e6b6ec35ed38b9675bccba17b3faaa714015b08b3572a4c44b005e0cb6e2074434c9c5e81633896665db5c7ddcbf31b9ac994eb211c9f911aa32fdd6bc711fe604022a108e9e8cb6ee0a23da4effa4201fb122f260053e7e92bef420be6d8a92d4242cc0199849fe6d8d0ef366fa846412e6df5

### IDENTIFIANT PC CLINIC
    email : bastienbrave@vendeur.com
    password : Password1
    token : 454bfd3ef98907c15f779b541e30cda6b3b890f87a7e785c33cf6bc87bd364cd79bffea7e366ecf3223c8bf00e01ab58e130e24365a2147c8b3d46bb5924b01321679b8a0dbc5ebf5a7674dec14d3625aaf9548ea951afb664f645aee5a7d400be821dc9382a3da780a782c1c9a02424c404832888f847fa9112b5fbc06caeef


## COMMENT UTILISER L'API DANS POSTMAN 

### POUR VISUALISER TOUS LES ARTICLES D'UNE CATEGORIE

Tout d'abord il faut commencer par aller en l'onglet "Authorization", séléctionner "BEARER TOKEN" rentré le token de votre choix fourni ci-dessus. Ce Mettre en catégorie GET et coller cet url : "http://localhost:1337/api/billet-reducs". Appuyez sur SEND et vous verrez que ça affiche tous les produits qui sont dans la catégorie Billet-Réduc. Vous pouvez faire de mêmes avec ces url : 
- "http://localhost:1337/api/france-billets"
- "http://localhost:1337/api/mister-good-deals"
- "http://localhost:1337/api/nature-and-decouvertes"
- "http://localhost:1337/api/pc-clinics"
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"

### POUR VISUALISER UN ARTICLE EN PARTICULIER D'UNE CATEGORIE 

Tout d'abord il faut commencer par aller en l'onglet "Authorization", séléctionner "BEARER TOKEN" rentré le token de votre choix fourni ci-dessus. Ce Mettre en catégorie GET et coller cet url : "http://localhost:1337/api/billet-reducs/1" (le "1" correspond à l'id autrement dit "/:id"). Appuyez sur SEND et vous verrez que ça affiche le produit correspondant à l'id que vous avez choisis. Vous pouvez faire de mêmes avec ces url : 
- "http://localhost:1337/api/france-billets"
- "http://localhost:1337/api/mister-good-deals"
- "http://localhost:1337/api/nature-and-decouvertes"
- "http://localhost:1337/api/pc-clinics"
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"

### POUR AJOUTER UN ARTICLE DANS UNE CATEGORIE 

Tout d'abord il faut commencer par aller en l'onglet "Authorization", séléctionner "BEARER TOKEN" rentré le token correspondant à la catégorie dans laquelle vous souahitez poster un nouvelle article. Ce Mettre en catégorie POST et coller cet url : "http://localhost:1337/api/billet-reducs". Allez dans l'onglet Body selectionnez raw, puis ce mettre en format JSON. Une fois tout cela fait vous pouvez rentrer le code fourni ci dessous en l'adaptant selon votre besoin.

    {
        "data": {
                "Nom": "Tommy",
                "Description": "Concert de Tommy Hilfiger",
                "Type": "Concert",
                "Prix": 15,
                "Stock": 60
            }
    }

Vous pouvez faire de mêmes avec ces url : 
- "http://localhost:1337/api/france-billets"
- "http://localhost:1337/api/mister-good-deals"
- "http://localhost:1337/api/nature-and-decouvertes"
- "http://localhost:1337/api/pc-clinics"
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"

Appuyez sur SEND et vous verrez que l'article à bien été supprimé.

### POUR MODIFIER UN ARTICLE DANS UNE CATEGORIE 

Tout d'abord il faut commencer par aller en l'onglet "Authorization", séléctionner "BEARER TOKEN" rentré le token correspondant à la catégorie dans laquelle vous souahitez modifier un article resistant. Ce Mettre en catégorie PUT et coller cet url : "http://localhost:1337/api/billet-reducs/1" (le "1" correspond à l'id autrement dit "/:id"). Allez dans l'onglet Body selectionnez raw, puis ce mettre en format JSON. Une fois tout cela fait vous pouvez rentrer le code fourni ci dessous en l'adaptant selon votre besoin.

    {
        "data": {
                "Nom": "Tommy",
                "Description": "Concert de Tommy Hilfiger",
                "Type": "Concert",
                "Prix": 15,
                "Stock": 60
            }
    }

Vous pouvez faire de mêmes avec ces url : 
- "http://localhost:1337/api/france-billets"
- "http://localhost:1337/api/mister-good-deals"
- "http://localhost:1337/api/nature-and-decouvertes"
- "http://localhost:1337/api/pc-clinics"
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"

Appuyez sur SEND et vous verrez que l'article à bien été modifié.

### POUR SUPPRIMER UN ARTICLE DANS UNE CATEGORIE 

Tout d'abord il faut commencer par aller en l'onglet "Authorization", séléctionner "BEARER TOKEN" rentré le token correspondant à la catégorie dans laquelle vous souahitez supprimer un article resistant. Ce Mettre en catégorie DELETE et coller cet url : "http://localhost:1337/api/billet-reducs/1" (le "1" correspond à l'id autrement dit "/:id"). Appuyez sur SEND et vous verrez que ça à bien supprimé produit correspondant à l'id que vous avez choisis. Vous pouvez faire de mêmes avec ces url : 
- "http://localhost:1337/api/france-billets"
- "http://localhost:1337/api/mister-good-deals"
- "http://localhost:1337/api/nature-and-decouvertes"
- "http://localhost:1337/api/pc-clinics"
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"


# PARTIE FRONT-END

## LES USERS 

### IDENTIFIANT VENDEUR GENERAL
    email : nicolas@test.com
    password : Password1

### IDENTIFIANT VENDEUR BILLET-REDUC
    email : virginie@test.com
    password : Password1

### IDENTIFIANT VENDEUR FRANCE-BILLET 
    email : sebastien@test.com
    password : Password1

### IDENTIFIANT VENDEUR MISTER GOOD DEAL
    email : christian@test.com
    password : Password1

### IDENTIFIANT VENDEUR NATURE & DECOUVERTE
    email : alexis@test.com
    password : Password1

### IDENTIFIANT VENDEUR PC.CLINIC
    email : lorence@test.com
    password : Password1

### IDENTIFIANT VENDEUR VANDEN-BORRE
    email : maxime@test.com
    password : Password1

### IDENTIFIANT VENDEUR WE-FIX
    email : florent@test.com
    password : Password1

## UTILISATION DU DE L'APPLICATION WEB 

Après bien avoir suivie l'aide au démarrage ci-dessus, vous êtes sensé vous retrouver sur la page de Login. Comme vous pouvez voir dans l'url vous êtes sur la page 
"/login" si vous essayez de supprimer ce /login pour directement atterire sur la Home Page ça ne fonctionnera pas car toutes les autres pages sont sécurisées et sont accéssible uniquement quand on est connecté. Renseigné l'email et le mot de passe d'un user fourni juste au dessus. Parfait vous êtes bien connectés et vous avez bien été redirigée sur la Home Page. Comme vous pouvez le voir en haut à droite vous avez un bouton "LOGOUT" qui vous permet de vous déconnecter. Juste en dessous vous avez également d'autre bouton qui vous permet d'accéder aux espaces des différent magasin. Lorsque vous cliquez sur ses boutons vous êtes redirigé sur l'espace de la boutique choisis et vous pouvez donc visualiser les articles en ligne. En fonction de l'user que vous utiliser, dans l'espace de votre boutique et vous pouvez ajouter un article en remplissant les champs nécessaire. Et vous pouvez aussi supprimer un produit en cliquant sur le bouton prévus à cet effet. 

# FIN

Merci de m'avoir fait confiance sur ce projet et d’avoir pris le temps de lire le manuel d’utilisation pour une utilisation optimale pour tout type de personne. Si jamais vous rencontrez quelconque problème vous pouvez me contactez je répondrais dans les plus brefs délais.

Merci.


# EN - SALEZI 

## INTRODUCTION

**Hello, this is the user guide for the Salezi project. This project was carried out for FNAC, in which we had to develop a robust and secure API for managing the stocks and sales of commercial partners such as France-Billet,... . To achieve this, we'll be using Strapi with a SQLite database. The aim is to enable the various users (Super Admin, Fnac Manager, Vendor) to easily and efficiently manage their products and sales, as well as inventory management. This project will facilitate collaboration between FNAC and its partners. To take it a step further, I created a website to act as the api front-end.**

To make this project I started by installing Strapi, then I created a SQLite database. Then I created a GIT repository so that I could access my project at any time. Once I'd done all that, I went to Strapi's administrator interface and configured the back-end (collections, roles, users, tokens, etc.). I also made sure that the back-end was secure. Finally, I went into postman to test all my API routes and created a folder for you to use with postman. Then I set about coding a secure front-end for this API.

## START-UP

1. Open the folder I've provided in vs code. 
2. Open the vs code terminal.
3. Write this command "npm run develop" (make sure you're in my-project).
4. Now click on the admin link in the terminal.
5. Log in with the SuperAdmin credentials provided below.
6. Open another terminal and write this command "npm start" (make sure you're in salezi-react). 
7. Normally, a web page will start automatically.
8. Perfect, now run the Postman file I've provided.
9. That's it, you're ready to go.

## POSTMAN CREDENTIALS

### SUPER ADMIN LOGIN
    email : superadmin@fnac.com
    password : Password1
    token : "377d6d2964ddcf1c0c2956d6aa45494aa15902a6f351931fce2475e46fa82497089385d39bdda764ef02acaf116d3fb9c9807cfee7786a1cfa459ce919e57c79592cb8deb29ee75fe45ad6f65b6b5a529fef63d3690a96410f83a7d50ffa3a56cdd8c79e808d7866692b914d747b4db78dcb48b47ec4ade13cf4466cb19bacdd"

### FNAC MANAGER LOGIN
    email : clara38@manager.com
    password : Password1
    token : "0062b212dac50375eb48d922629a774695f8a062f790773abc5cdd6c17bb5869e0e8080e5c3d4c8d111e5ef8fc37a49f49f51fc17c2bc258aca5ed8329668b96451547f25a8b6e69ecb370ed9b86f04756e661a61a5588904ac2feed67f0d1502f2366ab55c069a0ac264e54a19a833f83b1f254f562c3198ef3f249ceadb6a6"

### GENERAL VENDOR LOGIN
    email : marcusdelavega@vendeur.com
    password : Password1
    token : "8ed9054c3457e3eb24d2f532e05a1f2a05fa45dc6cdfca85aea8777d9c789c16209d4d5e0125e1728f26ae34a03b12f223d939dfd8c330b97e1483b5ed7d2052f31bd03753c8410ae02d6f1017a5523a2414d0c8e5adf53b5c15b46f49474be3f6479f557a3b50cac8ab7e2ad5d9cbf5e54bd008318abe9c2edff6488b7e9f3c"
    
### IDENTIFIANT VENDEUR FRANCE-BILLET
    email : elodieetoile@vendeur.com
    password : Password1
    token : "308704a5f1164bd872affdaaa66b55da6fe79661189b968b3cdf4b39893819a9c21e5d7cf6117421ed1e4e2b3d2f030a346eac8f2d625950dd5dc504859178e810e341cb6a5e48f51c5c08440662a2669bf0763da199db2c2f886fadce058084dca107cfbd496eccfe7dbcf0e620f589120f5e9c77afedd85065f6d4899cf908"

### IDENTIFIANT VENDEUR MISTER GOOD DEAL
    email : theophiletrendy@vendeur.com
    password : Password1
    token : "2117079a1afec8dae2960487a19884cffe4e2063e2d53f9bf85d76b98220539ff88386c9280a9ef3d75c93dff8e8125312c1fd767bdfde1a13f32e35803cf7e7628dcd5c152f602a0f3b939e0203ec052b89e8b976aa4d89211d7e6249b4f2869afebe031fa8ec9ecf46050cc547cd3250b32f1bb8faa3a3db2aa3bdad6ce5bf"

### IDENTIFIANT VENDEUR WEFIX
    email : maximystique@vendeur.com
    password : Password1
    token : "bcbba8eaa37bec5a494f59ca69a77e9be3ab4a6ad8c87f99289de99e33db1f996189ed36097a325152fce0a2530b9b46ed86d41bda19d79b826cc848247eb09f4920c6a7ac70531a1d8d4e78c318adeb5b957c3575c594823e353a174cad730ec1c72424e3c77cd21bc8f0ac41ab3fddabd25668e4f56ea982be5c30e1cb70a3"

### IDENTIFIER VENDEUR BILLET-REDUC
    email : leandrelumiere@vendeur.com
    password : Password1
    token : "d32a787c79b934ae0c36cf29887f1620b8186d0d6ab5eef9792925788c736648ed1110a08d98f793a980c53cb14c664a16332db6e34a6df4bfeda5b83f96066ab4055288e86a71e168fb5f8013b93132f0fc24252b594e015134e35eeba9faa13a7ad89d7abfec51d52df1a3da43fd9cf612bf7ee4fc3aa09e90e8bab09da823"

### SELLER LOGIN VANDEN BORRE
    email : aurelieartive@vendeur.com
    password : Password1
    token : "47a72efae4b4946c13df2e064e9512872679d91b629a543e56094396e7502dc6ffe71e4249ff6c368ea8186884cdb6e82fd3601c4b9188312fab813000daf1057661e70ce9499e7ac7ad50a39bc7af3b125ce27fe917eda69d0d0aeef47667838ce5ac9786f9c8a3ca9c929abcfbda3b036738dfecb523f39ee38e3a0cc05182"

### SELLER IDENTIFIER NATURE & DÉOUVERTE
    email : alexisciel@vendeur.com
    password : Password1
    token : "3e1031e0a5c0f0089271b2913e6b6ec35ed38b9675bccba17b3faaa714015b08b3572a4c44b005e0cb6e2074434c9c5e81633896665db5c7ddcbf31b9ac994eb211c9f911aa32fdd6bc711fe604022a108e9e8cb6ee0a23da4effa4201fb122f260053e7e92bef420be6d8a92d4242cc0199849fe6d8d0ef366fa846412e6df5"

### PC CLINIC LOGIN
    email : bastienbrave@vendeur.com
    password : Password1
    token : "454bfd3ef98907c15f779b541e30cda6b3b890f87a7e785c33cf6bc87bd364cd79bffea7e366ecf3223c8bf00e01ab58e130e24365a2147c8b3d46bb5924b01321679b8a0dbc5ebf5a7674dec14d3625aaf9548ea951afb664f645aee5a7d400be821dc9382a3da780a782c1c9a02424c404832888f847fa9112b5fbc06caeef"

## HOW TO USE THE API IN POSTMAN 

### TO VIEW ALL ARTICLES IN A CATEGORY

First of all, go to the "Authorization" tab, select "BEARER TOKEN" and enter the token of your choice provided above. Put it in the GET category and paste this url: "http://localhost:1337/api/billet-reducs". Press SEND and you'll see that it displays all the products in the Billet-Réduc category. You can do the same with these urls: 
- "http://localhost:1337/api/france-billets"
- http://localhost:1337/api/mister-good-deals
- http://localhost:1337/api/nature-and-decouvertes
- http://localhost:1337/api/pc-clinics
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"

### TO VIEW A SPECIFIC ITEM IN A CATEGORY 

First of all, go to the "Authorization" tab, select "BEARER TOKEN" and enter the token of your choice provided above. Put it in the GET category and paste this url: "http://localhost:1337/api/billet-reducs/1" (the "1" corresponds to the id, i.e. "/:id"). Press SEND and you'll see that it displays the product corresponding to the id you chose. You can do the same with these urls: 
- "http://localhost:1337/api/france-billets"
- http://localhost:1337/api/mister-good-deals
- http://localhost:1337/api/nature-and-decouvertes
- http://localhost:1337/api/pc-clinics
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"
### TO ADD AN ITEM TO A CATEGORY 

First of all, go to the "Authorization" tab, select "BEARER TOKEN" and enter the token corresponding to the category in which you wish to post a new article. Put it in the POST category and paste this url: "http://localhost:1337/api/billet-reducs". Go to the Body tab, select raw, then set this to JSON format. Once you've done all this, you can enter the code provided below, adapting it to your needs.
    {
        "data": {
                "Name": "Tommy",
                "Description": "Tommy Hilfiger concert",
                "Type": "Concert",
                "Price": 15,
                "Stock": 60
            }
    }
You can do the same with these urls: 
- "http://localhost:1337/api/france-billets"
- "http://localhost:1337/api/mister-good-deals"
- "http://localhost:1337/api/nature-and-decouvertes"
- "http://localhost:1337/api/pc-clinics"
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"
Press SEND and you'll see that the item has been deleted.

### TO MODIFY AN ARTICLE IN A CATEGORY 

First of all, go to the "Authorization" tab, select "BEARER TOKEN" and enter the token corresponding to the category in which you wish to modify a resistant article. Put it in the PUT category and paste this url: "http://localhost:1337/api/billet-reducs/1" (the "1" corresponds to the id, i.e. "/:id"). Go to the Body tab, select raw, then set this to JSON format. Once you've done all this, you can enter the code provided below, adapting it to your needs.
    {
        "data": {
                "Name": "Tommy",
                "Description": "Tommy Hilfiger concert",
                "Type": "Concert",
                "Price": 15,
                "Stock": 60
            }
    }
You can do the same with these urls: 
- "http://localhost:1337/api/france-billets"
- "http://localhost:1337/api/mister-good-deals"
- "http://localhost:1337/api/nature-and-decouvertes"
- "http://localhost:1337/api/pc-clinics"
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"
Press SEND and you'll see that the item has been modified.

### TO DELETE AN ARTICLE FROM A CATEGORY 

First of all, go to the "Authorization" tab, select "BEARER TOKEN" and enter the token corresponding to the category in which you wish to delete a resistant article. Put it in the DELETE category and paste this url: "http://localhost:1337/api/billet-reducs/1" (the "1" corresponds to the id, i.e. "/:id"). Press SEND and you'll see that it has deleted the product corresponding to the id you chose. You can do the same with these urls: 
- "http://localhost:1337/api/france-billets"
- http://localhost:1337/api/mister-good-deals
- http://localhost:1337/api/nature-and-decouvertes
- http://localhost:1337/api/pc-clinics
- "http://localhost:1337/api/vanden-borres"
- "http://localhost:1337/api/we-fixes"

# FRONT-END PART

## USERS

### GENERAL VENDOR LOGIN
    email : nicolas@test.com
    password: Password1

### BILLET-REDUC SELLER LOGIN
    email: virginie@test.com
    password : Password1

### IDENTIFIER VENDEUR FRANCE-BILLET 
    email: sebastien@test.com
    password : Password1

### SELLER LOGIN MISTER GOOD DEAL
    email: christian@test.com
    password : Password1

### SELLER LOGIN NATURE & DECOUVERTE
    email: alexis@test.com
    password : Password1

### SELLER LOGIN PC.CLINIC
    email: lorence@test.com
    password : Password1

### SELLER LOGIN VANDEN-BORRE
    email: maxime@test.com
    password : Password1

### WE-FIX SELLER ID
    email : florent@test.com
    password : Password1

## USING THE WEB APPLICATION 

After following the start-up help above, you should be on the Login page. As you can see from the url, you're on page 
"If you try to delete this /login and go straight to the Home Page, it won't work, as all the other pages are secure and only accessible when you're logged in. Enter the email and password of the user provided above. Perfect, you're logged in and you've been redirected to the Home Page. As you can see, in the top right-hand corner there's a "LOGOUT" button that lets you log out. Just below it you'll also find another button that allows you to access the different store areas. When you click on these buttons, you'll be redirected to the store area you've chosen, where you can view the items online. Depending on the user you're using, you can add an item to your store by filling in the necessary fields. You can also delete a product by clicking on the appropriate button. 

# END

Thank you for trusting me with this project and for taking the time to read the user manual for optimal use by all types of people. If you have any problems, please contact me and I'll get back to you as soon as possible.
I'll get back to you as soon as possible.