---
title: 'Mon dernier article'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Mar 18 2025'
heroImage: '/blog-placeholder-3.jpg'
---

## Introduction à Tailwind CSS

Tailwind CSS est un framework CSS utilitaire qui permet de créer des interfaces utilisateur modernes et réactives rapidement. Contrairement aux frameworks traditionnels comme Bootstrap, Tailwind offre une approche "utility-first", où vous appliquez directement des classes CSS aux éléments HTML pour styliser votre contenu.

## Pourquoi utiliser Tailwind CSS ?

1. **Flexibilité** : Tailwind vous permet de personnaliser chaque aspect de votre design sans être limité par des composants préconstruits.
2. **Rapidité** : Grâce à ses classes utilitaires, vous pouvez styliser vos éléments directement dans le HTML, ce qui accélère le développement.
3. **Personnalisation** : Avec le fichier `tailwind.config.js`, vous pouvez ajuster les couleurs, les espacements, les polices et bien plus encore pour correspondre à votre identité visuelle.

## Exemple de code

Voici un exemple simple d'utilisation de Tailwind CSS pour créer une carte :

```html
<div class="max-w-sm mx-auto bg-white rounded-lg shadow-md overflow-hidden">
    <img class="w-full h-48 object-cover" src="/path-to-image.jpg" alt="Image">
    <div class="p-4">
        <h2 class="text-xl font-semibold text-gray-800">Titre de la carte</h2>
        <p class="text-gray-600 mt-2">Ceci est une description rapide de la carte.</p>
        <button class="mt-4 px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-600">
            En savoir plus
        </button>
    </div>
</div>
```

## Conclusion

Tailwind CSS est un outil puissant pour les développeurs qui souhaitent créer des designs personnalisés rapidement et efficacement. Si vous ne l'avez pas encore essayé, c'est le moment idéal pour l'intégrer dans vos projets.

Pour en savoir plus, visitez le site officiel de [Tailwind CSS](https://tailwindcss.com/).

## Galerie d'images avec Flexbox

Voici un exemple d'utilisation de Tailwind CSS pour afficher une galerie d'images en flex :


<div class="flex flex-wrap gap-4 justify-center">
    <div class="w-1/4">
        <img class="rounded-lg shadow-md" src="https://picsum.photos/200/300?random=1" alt="Image 1">
    </div>
    <div class="w-1/4">
        <img class="rounded-lg shadow-md" src="https://picsum.photos/200/300?random=2" alt="Image 2">
    </div>
    <div class="w-1/4">
        <img class="rounded-lg shadow-md" src="https://picsum.photos/200/300?random=3" alt="Image 3">
    </div>
    <div class="w-1/4">
        <img class="rounded-lg shadow-md" src="https://picsum.photos/200/300?random=4" alt="Image 4">
    </div>
</div>


Cette galerie utilise `flex-wrap` pour permettre aux images de s'adapter à différentes tailles d'écran, tout en maintenant un espacement uniforme grâce à `gap-4`.