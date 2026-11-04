# BOB & CO — bob & co bv

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `bobandco.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/bobandco.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs bobandco` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@bobandco.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (€[MONTANT] / €[MONTANT] / Refusé €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
We are BOB & CO, a business and management consultancy based on Avenue des Arts in Brussels and working since 2010. One question decides more about a consultancy arrangement than anything written into the contract, and it is whether the work is genuinely performed independently. Belgian law looks at four things: what the parties agreed, whether the consultant is free to organise their working time, whether they are free to organise the work itself, and whether anyone is in a position to exercise hierarchical authority over them. The fourth is decisive, because hierarchical authority is simply incompatible with self-employed status and no clause in a contract can neutralise it. What counts is how the relationship is actually performed, not what it is called. That matters because requalification is expensive for both sides: social security contributions are recalculated, employer and employee shares alike, with surcharges and interest, and employment claims can follow. So we raise it before a mission is defined rather than after an inspection, and we define missions by deliverable and deadline rather than by presence and instruction. We are also not auditors, lawyers or financial advisers, and we say where a question belongs elsewhere. Site: bobandco.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
