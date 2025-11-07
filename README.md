# Formation JavaScript - 10 Exercices Pratiques

Une série de 10 exercices progressifs pour apprendre JavaScript de manière pratique, sans framework ni API externe.

## 📚 À propos

Cette formation est conçue pour les **apprenants débutants et intermédiaires** en développement web. Chaque exercice se concentre sur des compétences JavaScript essentielles avec une difficulté progressive.

### Technologies utilisées
- **HTML5** - Structure sémantique
- **TailwindCSS** (via CDN) - Styling moderne et responsive
- **JavaScript Pur** - Aucun framework, aucune API externe

## 🚀 Démarrage rapide

1. Clonez ou téléchargez ce dépôt
2. Ouvrez `index.html` dans votre navigateur
3. Choisissez un exercice et commencez à coder !

```bash
# Cloner le projet
git clone [URL_DU_REPO]

# Naviguer dans le dossier
cd JS_exe

# Ouvrir dans le navigateur
open index.html
```

## 📂 Structure du projet

```
JS_exe/
├── index.html              # Page d'accueil avec menu de navigation
├── README.md              # Ce fichier
└── exercices/
    ├── ex01/              # Exercice 1 : Compteur
    │   ├── index.html
    │   └── script.js
    ├── ex02/              # Exercice 2 : Générateur de couleurs
    │   ├── index.html
    │   └── script.js
    ├── ex03/              # Exercice 3 : Afficher/Masquer
    │   ├── index.html
    │   └── script.js
    ├── ex04/              # Exercice 4 : Todo List
    │   ├── index.html
    │   └── script.js
    ├── ex05/              # Exercice 5 : Calculatrice
    │   ├── index.html
    │   └── script.js
    ├── ex06/              # Exercice 6 : Quiz Interactif
    │   ├── index.html
    │   └── script.js
    ├── ex07/              # Exercice 7 : Horloge Numérique
    │   ├── index.html
    │   └── script.js
    ├── ex08/              # Exercice 8 : Générateur de mots de passe
    │   ├── index.html
    │   └── script.js
    ├── ex09/              # Exercice 9 : Galerie avec filtres
    │   ├── index.html
    │   └── script.js
    └── ex10/              # Exercice 10 : Jeu du Pendu
        ├── index.html
        └── script.js
```

## 🎯 Liste des exercices

### 🟢 Niveau Débutant

#### Exercice 1 : Compteur
**Notions :** `addEventListener`, `innerText`, `querySelector`, conditions
- Créer un compteur avec boutons d'incrémentation/décrémentation
- Bonus : Changer la couleur selon la valeur (négative, positive, nulle)

#### Exercice 2 : Générateur de Couleurs Aléatoires
**Notions :** `Math.random()`, `Math.floor()`, `style.backgroundColor`, template literals
- Générer et afficher des couleurs RGB aléatoires
- Bonus : Convertir en hexadécimal

#### Exercice 3 : Afficher/Masquer du Contenu
**Notions :** `classList.toggle()`, `classList.add()`, `classList.remove()`
- Afficher/masquer du contenu avec un bouton
- Bonus : Ajouter une animation de transition CSS

### 🟡 Niveau Intermédiaire

#### Exercice 4 : Todo List Basique
**Notions :** `createElement()`, `appendChild()`, `remove()`, gestion d'événements
- Créer une liste de tâches avec ajout et suppression
- Bonus : Marquer les tâches comme terminées

#### Exercice 5 : Calculatrice Simple
**Notions :** Opérateurs arithmétiques, `parseFloat()`, validation d'input
- Calculatrice 4 opérations avec gestion d'erreurs
- Bonus : Historique des 5 derniers calculs

#### Exercice 6 : Quiz Interactif
**Notions :** Tableaux d'objets, `forEach()`, conditions, compteurs
- Quiz de 5 questions à choix multiples avec score
- Bonus : Feedback visuel immédiat (vert/rouge)

#### Exercice 7 : Horloge Numérique en Temps Réel
**Notions :** `setInterval()`, `new Date()`, `getHours()`, `getMinutes()`, `getSeconds()`
- Horloge actualisée chaque seconde
- Bonus : Date complète et couleur selon moment de la journée

### 🔴 Niveau Avancé

#### Exercice 8 : Générateur de Mots de Passe
**Notions :** `Math.random()`, `charAt()`, boucles `for`, concaténation
- Générateur avec longueur personnalisable (8-20 caractères)
- Bonus : Options de caractères et bouton "Copier"

#### Exercice 9 : Galerie d'Images avec Filtres
**Notions :** `filter()`, `map()`, génération dynamique d'HTML
- Galerie avec filtres par catégorie
- Bonus : Barre de recherche et transitions

#### Exercice 10 : Jeu du Pendu
**Notions :** `split()`, `join()`, `includes()`, gestion d'état complexe
- Jeu complet avec 6 tentatives maximum
- Bonus : Visuel du pendu, catégories, rejouer sans recharger

## 💡 Comment utiliser ces exercices

1. **Ouvrez l'exercice** en cliquant sur la carte depuis la page d'accueil
2. **Lisez l'énoncé** attentivement dans le navigateur
3. **Ouvrez le fichier `script.js`** correspondant dans votre éditeur de code
4. **Codez votre solution** dans la zone prévue
5. **Testez en rafraîchissant** la page du navigateur
6. **Tentez les bonus** pour approfondir !

## 🎓 Conseils pédagogiques

- Progressez dans l'ordre pour une montée en compétence graduelle
- Ne regardez pas la solution tout de suite, cherchez d'abord
- Testez votre code fréquemment (console, `console.log()`)
- N'hésitez pas à consulter la documentation MDN
- Les bonus sont facultatifs mais recommandés pour aller plus loin

## 🛠️ Ressources utiles

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [JavaScript.info](https://javascript.info/)
- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [Can I Use](https://caniuse.com/) - Compatibilité navigateur

## 📝 Notes techniques

- Tous les fichiers HTML incluent TailwindCSS via CDN
- Les fichiers `script.js` sont chargés avec `defer` pour garantir le chargement du DOM
- Aucune dépendance npm requise
- Compatible avec tous les navigateurs modernes

## 🤝 Contribution

Si vous trouvez des bugs ou avez des suggestions d'amélioration :
1. Ouvrez une issue
2. Proposez une pull request
3. Partagez vos solutions créatives !

## 📄 Licence

Ce projet est libre d'utilisation à des fins pédagogiques.

---

**Bon apprentissage et bon code !** 🚀
