# 🎓 **TP – Analyse des besoins d’un client et création d’une maquette 100 % Bootstrap**

### **Durée : 2 heures**

### **Travail en binôme obligatoire**

### **Outil conseillé : [https://wireframe.cc](https://wireframe.cc)** (mais tout autre outil de wireframe est accepté)

---

# 🧩 **Contexte du TP**

Vous êtes sollicités pour concevoir la **maquette complète** du futur site web d’un artisan nommé **Stéphane**, gérant de la boutique *Les Mains du Vent*.
Stéphane n’est **pas du métier**, son expression est donc approximative et parfois floue : à vous de l’interpréter pour construire un site clair, structuré et réaliste.

⚠️ Vous ne codez PAS le site.
Vous réalisez uniquement **le wireframe / mockup** des pages.

---

# 🎯 **Objectifs du TP**

* Identifier les besoins exprimés avec un vocabulaire non technique
* Traduire ces besoins en **composants Bootstrap 5** (cards, grids, navbar, forms, carousel, etc.)
* Concevoir une **maquette complète d’un site web (5 pages)**
* Exercer son esprit d’analyse : décider ce qui est nécessaire même si le client ne l’a pas explicitement dit
* Produire une maquette structurée, cohérente, exploitable par un développeur

---

# 🚨 **Note importante : et la version mobile ?**

Stéphane, le client, n’a **jamais mentionné la responsivité**, ni l’existence d’une version mobile ou tablette.
Cela peut arriver dans la vraie vie : un client peut oublier de préciser un besoin essentiel.

➡️ **Liberté pédagogique**
Il vous revient donc, en tant que concepteurs, de décider :

* Faut-il prévoir une **version mobile / responsive** dans la maquette ?
* Comment les composants Bootstrap doivent-ils se comporter sur petit écran ?
* Quelles adaptations sont nécessaires (menu burger, colonnes qui passent en lignes, images réduites, etc.) ?

Vous utiliserez pour cela **vos connaissances de Bootstrap** et votre sens de l'analyse UX.

📌 *Vous n’êtes pas obligés de fournir une version mobile complète,
mais votre travail doit clairement indiquer :*

* soit un comportement responsive dans le wireframe,
* soit une justification écrite expliquant votre choix.

---

# 📄 **Brief du client – Discussion retranscrite**

Vous devez lire attentivement le dialogue ci-dessous.
C’est votre **unique base** pour concevoir le site.

---

## **Échange 1 – Discussion sur la page d’accueil (20 minutes de conversation retranscrite)**

> « Alors… voilà, pour l’accueil, je veux qu’on comprenne immédiatement que *c’est nous*. Quand je dis “nous”, je parle de ma boutique. Beaucoup de gens pensent qu’on est une sorte de coopérative, alors que non : c’est juste moi et ma femme. Donc j’aimerais une grande image, un truc qui claque un peu, mais pas trop flashy non plus.
>
> J’ai vu un site où il y avait un grand bandeau en haut, avec une phrase au milieu genre *Nos produits, votre bien-être*, tu vois ? On pourrait faire un truc comme ça. Je crois que ça s’appelle un… “header image” ? Ou un “image-banner” ? Je ne sais plus. Enfin un truc qui prend toute la largeur.
>
> Ah oui, et très important : j’aimerais qu’on voie notre slogan. Enfin… on n’a pas encore décidé du slogan. On hésite entre *Nature & Tradition* et *Le vent dans les mains, l’art dans le cœur*. Je ne sais pas si c’est important pour toi, mais si tu dois mettre une phrase, mets ce que tu veux pour l’instant.
>
> Et puis je veux absolument qu’on explique nos trois grandes familles de produits : les savons, les bougies, et les objets en bois. Les gens confondent souvent. J’aimerais trois petits encadrés avec, je sais pas, une icône ou une photo peut-être ? Tu t’y connais mieux que moi.
>
> Ah oui ! Et j’ai oublié : il faudrait qu’on puisse aussi mettre nos produits phares quelque part. On en a trois qui marchent bien, mais parfois on en change. Donc si on peut mettre des “vignettes”, comme des petites fenêtres avec une image, un nom, et peut-être une phrase, ce serait top.
>
> Et tout en bas, ou au milieu, enfin quelque part, il faudrait une petite zone sur moi. Pas un roman, juste deux lignes.
> Mais attention : pas la photo ! On n’a pas de photo professionnelle, et la dernière fois qu’on a essayé d’en faire une avec le portable, le chien s’est mis devant. Donc pas de photo de moi pour l’instant.
>
> Ah, et quelqu'un m’a dit qu'il fallait mettre un bouton pour “voir tous nos produits”… Si tu penses que c’est utile, mets-le. Je n’y connais rien. »
 

---


## **Échange 2 – Discussion sur la page Produits (conversation confuse et détaillée)**

> « Alors pour la page Produits… Comment expliquer… Je veux que ça fasse boutique en ligne, mais *sans être une boutique en ligne*. Je veux dire : ça ne vend rien directement. C’est plus pour montrer.
>
> J’aimerais que les produits soient dans des petites boîtes toutes identiques. Il ne faut surtout pas que certaines soient plus grandes que d’autres, sinon ça fait cheap. Peut-être des carrés, ou des rectangles… mais identiques. Et qu'il y ait un petit bouton, je ne sais pas comment on dit… *un truc pour cliquer dessus* et voir plus de détails.
>
> Avant d’afficher la liste, j’aimerais un moyen de choisir parmi nos trois catégories : savons, bougies, bois. Je ne veux pas un menu déroulant, ça fait vieillot. J’ai vu un site où on pouvait cliquer sur des sortes de petites étiquettes, et ça changeait ce qui était en dessous. Tu sais ce que je veux dire ?
>
> Et puis je veux que ce soit “propre”. Ma femme dit qu’il faut que l’espace respire, qu’il faut des marges, des blancs… Je ne sais pas si c’est technique pour toi.
>
> Ah oui, et parfois on a un produit hors catégorie, comme une bougie sculptée ou un savon cadeau. Il faudra peut-être prévoir une étiquette “Autres” un jour, donc si tu peux laisser un peu de place quelque part pour ça dans la maquette, ça serait bien.
>
> Et… est-ce qu'on doit mettre un texte en haut pour présenter la boutique ? Je ne sais pas. Le site de mon cousin a un texte en haut de chaque page, mais ça fait beaucoup de lecture. À toi de voir. »


---

## **Échange 3 – Discussion sur la fiche produit (beaucoup d’informations inutiles)**

> « Quand on clique sur un produit, j’aimerais que la page soit très simple.
> Avec une grande photo. Pas comme celle de mon téléphone hein, une belle photo professionnelle. On n’en a pas encore, mais on va en faire.
>
> Et à côté, ou en dessous sur petit écran, il faudrait mettre le prix. Le prix n'est pas très important parce que ce n’est pas un vrai site de vente, mais quand même il faut l'afficher.
>
> Ensuite une description : par exemple pour les savons, ils sont faits à la main, séchés deux semaines, etc. Mais la description peut parfois être très longue. Sur un site, j’ai vu un paragraphe énorme qui dépassait la page. Je ne veux pas ça. Peut-être mettre juste un aperçu ? Ou alors un texte court. Je te laisse décider, tu t’y connais mieux.
>
> Et en dessous, j’aimerais un endroit où mettre quelques produits similaires, trois ou quatre, ou même cinq si tu veux. Enfin… pas trop non plus.
>
> Ce serait bien aussi qu'il y ait un petit bouton “Acheter”, même si ça n’achète rien. C’est juste pour que les gens comprennent qu’éventuellement, un jour, on pourra vendre.
>
> Ah, j’allais oublier ! Tu sais sur les sites, parfois il y a des partages sur Facebook et tout ça ? Je ne veux surtout pas ça. Je trouve ça moche. Donc ne mets *aucun truc de réseaux sociaux* sur la page produit.
>
> Et si la photo est en portrait ou en paysage, est-ce que ça change quelque chose ? Tu gères ça toi-même, hein. »


---

## **Échange 4 – Discussion sur la page Contact (client très dispersé)**

> « Pour contacter la boutique, alors…
> Il faudrait un formulaire. Le plus simple possible : nom, mail, message. Rien d’autre.
> On nous a dit qu’on devrait demander le numéro de téléphone mais… non, je n’ai pas envie. Trop de contraintes. Et puis de toute façon les gens ne mettent jamais leur vrai numéro.
>
> Ensuite, j’aimerais que les horaires et notre adresse soient affichés quelque part, genre en colonne sur le côté.
>
> Je voulais aussi mettre une carte Google, mais j’ai essayé d’en mettre une sur mon blog l’an dernier et ça a tout cassé. Donc non, juste une image qui ressemble à une carte, ça ira.
>
> Est-ce qu’il faut un captcha ? Je ne veux pas que les gens doivent cliquer sur des feux rouges… On verra ça plus tard.
>
> Ah oui, on aimerait aussi mettre une phrase au début du genre : *“Écrivez-nous, nous vous répondrons au plus vite !”*
> Enfin, tu mets une phrase sympa, pas trop longue.
>
> Si tu penses qu’il faut une autre section, tu peux le dire. Mais surtout : pas de réseaux sociaux ici non plus, je n’aime vraiment pas ça. »

---

## **Échange 5 – Navigation, footer, pages diverses (client hésitant)**

> « Sur toutes les pages, je veux un petit menu en haut. Pas immense, pas comme sur les gros sites. Un truc simple avec trois liens : Accueil, Nos produits, Contact.
> Si tu trouves que *À propos* mérite un lien dans le menu, dis-le moi. Moi je ne sais pas trop où le mettre.
>
> Pour le bas de page, alors là…
>
> Je veux un truc propre, mais pas un bloc énorme. Sur un site j’ai vu un footer qui prenait la moitié de l’écran, j’ai quitté immédiatement. Donc je veux un footer, mais petit.
>
> Je veux qu’il y ait : mentions légales, lien vers mes réseaux (mais attention ! Je ne veux PAS les mettre en haut du site. En bas seulement, et tout petits), mon numéro SIRET.
>
> Et si possible, qu’il y ait une phrase genre : *“Les Mains du Vent – Artisanat local depuis 2014”*.
>
> Ah, et mon cousin m’a dit d’ajouter un truc pour accepter les cookies. Je ne sais pas comment ça marche. Tu peux faire un truc stylé, mais pas trop voyant. Tu es libre.
> Enfin… si c’est nécessaire. Je ne sais pas si ça l’est. »

---

## **Échange 6 – Le client ne parle JAMAIS de responsivité**

> « Ah, tu sais, moi je regarde mon site sur mon ordinateur. Je n’ai jamais trop regardé sur le téléphone, je trouve ça petit.
> Les gens aujourd’hui tout regardent sur leur téléphone, mais bon… moi je suis old school (rires).
> Enfin si tu veux faire en sorte que ce soit joli sur téléphone, tu peux hein… Je suppose que c’est mieux.
> Mais moi j’y connais rien, donc je ne te demande rien de particulier. Tu sais mieux que moi.
> De toute façon, quand je teste, je regarde juste sur mon PC portable. »

---

# 🧱 **Pages à créer (obligatoires)**

1. **Page d’accueil**
2. **Page liste des produits**
3. **Page fiche produit**
4. **Page contact**
5. **Page “À propos” / présentation détaillée**

---

# 📌 **Contraintes strictes**

✔ Vous utilisez **uniquement des composants Bootstrap 5**

✔ Votre maquette doit refléter fidèlement les demandes du client

✔ Vous décidez vous-même du traitement de la **responsivité**

✔ Le wireframe doit être simple, lisible et cohérent

❌ Pas de design fantaisie non prévu par Bootstrap

❌ Pas d’inventions qui n’existent pas dans le brief

❌ Pas d'animations non prévues par Bootstrap

---

# 🛠 **Travail à réaliser**

## **1. Analyse préliminaire (à rendre)**

Document bref contenant :

* Les 5 pages listées
* Les sections présentes dans chaque page
* Les composants Bootstrap choisis pour chaque section
* Une justification claire
* Votre décision concernant la responsivité :

  * soit un wireframe mobile en plus,
  * soit une description du comportement responsive,
  * soit une justification de votre choix.

---

## **2. Wireframes des 5 pages**

Attendus :

* Structure claire
* Composants Bootstrap identifiables
* Hiérarchie cohérente
* Responsivité indiquée ou expliquée
* Format PDF / PNG / lien web / photo acceptable

---

# 📤 **Livrables à remettre**

1️⃣ Analyse préliminaire (1 page)

2️⃣ Wireframes des 5 pages (images ou export PDF)

3️⃣ Notes éventuelles sur la responsivité

Un seul rendu par binôme si travail à deux.
