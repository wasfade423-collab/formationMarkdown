# Formation Markdow Novembre 2026

# La syntaxe de base

## Les titres

Les titres sont fait avec les **# il en faut 1 suivie de 1 espace pour un titre de niveau 1**; 2 suivies de 1 espace pour un titre de niveau 2

## Les Paragraphes

Pour faire un paragraph il suffit de sauter une ligne puis de commencer le Paragraphe sur la ligne suivante.  
Si dans un paragraphe vous souhaitez commencer une phrase sur une nouvelle ligne on fait (2 espaces) à la fin de la ligne qui s'achève.

## Les lignes de séparation

Pour faire une ligne de séparation (peut être entre 2 paragraphes) il faut faire --- sur une nouvelle ligne et  
Laisser une ligne vide avant la ligne des tirets

---

Laisser une ligne après la ligne des tirets

## Italique, le gras et la mise en exergue

Pour mettre un texte en _italique_ on utilise startTextestart sans espace.  
Pour mettre un texte en **gras** on utilise
startstartTextestartstart sans espace.

> Pour mettre en exerge on utilise (>+texte)

## Les listes

### Listes à puces

Pour le faire on met un tiret **-+1espace**

- Item 1
- Item 2
- Item 3

Pour faire une liste imbriqué on fait **2espaces+-+1espace** et on met le mot.

- Item 4
  - Sous-Item 4.1
- Item 5

### Les listes numérotés

Pour le faire on met au debut de chaque ligne 1 et l'editeur interprète.

1. Item 1
1. Item 2
   - Sous-Item 2.1
1. Item 3
   > Note: Pour l'imbriguation ici il faut mettre 3 espaces avant le tiret et le texte de la ligne imbriguée.

## Les Liens hypertextes

Pour faire un lien hypertexte, on met entre [] **crochets** le **nom qu'on souhaite afficher** sur le lien puis on le fait suivre du **lien** entre **parenthèses** ().

> Exemple: [Mon Portfolio](https://wasfolio.vercel.app)

## Les Images

Pour faire une image, on met un **pointd'exclamation** et entre [] **crochets** le **nom qu'on souhaite afficher** sur l'image(au cas où elle ne sera pas trouvé) puis on le fait suivre du **chemin vers l'image** entre **parenthèses** ().

> Exemple: ![Logo de Markdow](assets/logoMarkdow.jpg)

## Les extraits de code et blocs de code

### extraits de code

Pour insérer les extraits de code dans un markdow on utilise les **shifts** ``et y écrit le texte.  ` class Responsable {
private $nom;
}`

### Blocs de code

Pour insérer les blocs de code dans un markdow on utilise les **shifts** `````` on en met 3 au début et 3 à la fin.
**Exemeple:**

```PHP
    $fruits = ["apple", "banana", "cherry"];

    // Remove the first element
    $firstFruit = array_shift($fruits);

    echo $firstFruit; // Outputs: apple
    print_r($fruits);
    /* Outputs:
    Array
    (
        [0] => banana
        [1] => cherry
    )
    */
```

# La syntaxe étendue

## Tableau

- Pour creer les colonnes on utilise la barre verticale
- on sépare la première ligne (ligne d'etête) des autres lignes en utilisant des tirets en dessous de la ligne d'entpete.
- on utilise des **2points** pour gérer l'allignement.
  - Si on met le **2points** au milieu alors les élements de la collone est centré au milieu.
  - Si on met le **2points** à droite alors les élements de la collone est aligné à droite.
  - Si on met le **2points** à gauche alors les élements de la collone est aligné à gauche.

| Nom       | Prenom  | Date de Naissance |
| :-------- | :-----: | ----------------: |
| tonoukoin | Wasfade |      12 Juin 2025 |
| tonoukoin | claude  |      15 Mars 2020 |

## Les cases à cocher

Pour faire les cases à cocher on utilise une liste et on met **les crochets ** [] et dans ces crochets, on met :

- x pour cocher
- (espacee) pour décocher

> Exemple

- [x] Start Markdow formation
- [ ] finish the formation

## Exposant et Indice

### Exposant

Pour mettre un texte en **exposant** on l'entoure **<sup></sup>**

> Exemple: 1<sup>er</sup>

### Indice

Pour mettre un texte en **indice** on l'entoure de **<sub></sub>**

> Exemple: H<sub>2</sub>O

## Surlignage et texte barré

### Surligner

Pour surligne un texte on l'encadre de **double signes eguals**

> Exemple: ==Malade==

### Barrer

Pour barrer un texte on l'entoure de **double tildes**

> Exemple: ~~Mort~~

## Note de bas de Page et liens vers les titres

### Note de bas de Page

Note de bas de page [^1]

[^1]: Cette note est la 1<sup>ère</sup>

### Liens vers les titres

On peut ajouter un lien vers un titre en faisant: [titre](#la-syntaxe-de-base). Dans les **crochets** on met le nom qu'on veux afficher et dans les **parenthèses** on met le nom du titre.

# Autres éléments plus spécifiques

## Icones GFM

Le Markdown Github propose des codes courts sous la forme **:nom:** pou représenter des icônes colorées.  
Voici quelques uns:
| Icone | Code ourt GFM |
| :--- | :--- |
| :warning: | `:warning:` |
| :question: | `:question:` |
| :start: | `:star:` |

---

Les listes completes des codes courts est disponile à [cette Page](https://github.com/ikatyano) ce lien n'est pas correcte.
