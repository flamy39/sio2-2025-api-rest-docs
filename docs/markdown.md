# Introduction au langage Markdown

## 1. Qu'est-ce que Markdown ?

Markdown est un langage de balisage léger conçu pour formater du texte de manière simple et intuitive. Il permet de structurer et styliser du texte en utilisant une syntaxe facile à lire et à écrire. Son principal avantage est qu'il peut être converti en HTML sans nécessiter de connaissances avancées en développement web.

### 1.1 Rôle de Markdown
Markdown est couramment utilisé pour :
- La documentation technique (ex. : GitHub, GitLab, etc.).
- La rédaction d'articles et de blogs.
- La rédaction de fichiers README.
- La mise en forme des notes et contenus éducatifs.

### 1.2 Fonctionnement de Markdown
Le texte écrit en Markdown peut être lu directement sans mise en forme, mais il peut aussi être converti automatiquement en HTML ou affiché avec un style particulier dans des outils compatibles comme VS Code, GitHub, ou des générateurs de site statique.

---

## 2. Syntaxe de base de Markdown

### 2.1 Titres
Les titres sont définis en utilisant des `#`. Plus le nombre de `#` est grand, plus le titre est petit.

```markdown
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
```

### 2.2 Mise en forme du texte
Markdown permet de mettre en forme le texte facilement.

- **Gras** : `**Texte en gras**` → **Texte en gras**
- *Italique* : `*Texte en italique*` → *Texte en italique*
- ~~Barré~~ : `~~Texte barré~~` → ~~Texte barré~~

### 2.3 Listes

**Listes non ordonnées :**

```markdown
- Élément 1
- Élément 2
  - Sous-élément 2.1
  - Sous-élément 2.2
```

Affichage :
- Élément 1
- Élément 2
  - Sous-élément 2.1
  - Sous-élément 2.2

**Listes ordonnées :**

```markdown
1. Premier élément
2. Deuxième élément
3. Troisième élément
```

Affichage :
1. Premier élément
2. Deuxième élément
3. Troisième élément

### 2.4 Liens et images

**Liens :**

```markdown
[Nom du lien](https://exemple.com)
```

Affichage : [Nom du lien](https://exemple.com)

**Images :**

```markdown
![Texte alternatif](https://exemple.com/image.jpg)
```

### 2.5 Blocs de code
Markdown permet d'afficher du code en utilisant des accents graves ` ``` `.

```markdown
```php
<?php
echo "Bonjour, Markdown !";
```
```

Affichage :

```php
<?php
echo "Bonjour, Markdown !";
```

### 2.6 Citations

Les citations se créent avec le `>`.

```markdown
> Ceci est une citation en Markdown.
```

Affichage :
> Ceci est une citation en Markdown.

### 2.7 Tableaux
Markdown permet de créer des tableaux simplement.

```markdown
| Nom     | Âge | Métier      |
|---------|----|------------|
| Alice   | 25 | Développeuse |
| Bob     | 30 | Designer    |
```

Affichage :

| Nom     | Âge | Métier      |
|---------|----|------------|
| Alice   | 25 | Développeuse |
| Bob     | 30 | Designer    |

---

## 3. Syntaxe avancée

Markdown offre des fonctionnalités avancées permettant d'améliorer la mise en forme et la structuration des documents.

### 3.1 Liens avec titres
Il est possible d'ajouter un titre sur un lien qui s'affichera au survol :

```markdown
[Nom du lien](https://exemple.com "Titre du lien")
```

Affichage : [Nom du lien](https://exemple.com "Titre du lien")

### 3.2 Images avec dimensions
On peut redimensionner une image en combinant du HTML :

```markdown
<img src="https://exemple.com/image.jpg" alt="Texte alternatif" width="300" height="200">
```

### 3.3 Liens internes
Pour référencer une section interne du document, il suffit d'utiliser :

```markdown
[Aller à la section 2](#2-syntaxe-de-base-de-markdown)
```

### 3.4 Blocs de code spécifiques
Il est possible d’indiquer le langage de programmation pour un meilleur rendu syntaxique :

```markdown
```javascript
console.log("Bonjour, Markdown !");
```
```

Affichage :

```javascript
console.log("Bonjour, Markdown !");
```

### 3.5 Cases à cocher (Checklist)
Markdown permet de créer des listes avec des cases à cocher (pratique pour les TODOs) :

```markdown
- [x] Tâche terminée
- [ ] Tâche en cours
- [ ] Tâche à faire
```

Affichage :
- [x] Tâche terminée
- [ ] Tâche en cours
- [ ] Tâche à faire

### 3.6 Notes de bas de page
Markdown prend en charge les notes de bas de page :

```markdown
Ceci est un texte avec une note[^1].

[^1]: Ceci est la note de bas de page.
```

Affichage :
Ceci est un texte avec une note[^1].

[^1]: Ceci est la note de bas de page.

### 3.7 Séparateurs
On peut ajouter des séparateurs horizontaux pour structurer un document :

```markdown
---
```

---

## 4. Conclusion
Markdown est un langage simple et puissant permettant de structurer du texte de manière efficace. Il est largement utilisé dans le monde du développement et de la documentation. En maîtrisant sa syntaxe de base et avancée, vous pourrez rapidement rédiger du contenu clair et bien formaté sans effort.

