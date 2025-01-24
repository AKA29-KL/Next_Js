# Next.js Dashboard Tutorial

Ce fichier documente le processus de suivi du [tutoriel officiel de Next.js](https://nextjs.org/learn/dashboard-app/getting-started) pour construire une application de tableau de bord. Ce tutoriel couvre les bases de Next.js ainsi que des concepts avancés comme le rendu côté serveur (SSR), la gestion des composants Skeleton, et l’optimisation des polices et des images.

---

## Objectif du Tutoriel

L'objectif principal de ce tutoriel est de construire une application fonctionnelle de tableau de bord qui utilise les fonctionnalités de Next.js pour offrir des performances élevées et une navigation fluide. Il met l’accent sur :

- La création de composants dynamiques.
- L’utilisation de `Suspense` pour le rendu asynchrone.
- L'optimisation des ressources (polices, images).

---

## Étapes Suivies

### 1. **Initialisation du Projet**
- Configuration d'un projet Next.js avec `create-next-app`.
- Organisation initiale du répertoire avec des pages et des composants de base.

### 2. **Structure des Pages**
- Création de pages dans le répertoire `app`.
- Mise en place de la navigation interne avec des liens entre les pages.

### 3. **Rendu des Composants Dynamiques**
- Implémentation de composants qui affichent des données factices pour simuler des cas d’utilisation réels.

### 4. **Fetching des Données**
- Utilisation des méthodes `getStaticProps` et `getServerSideProps` pour récupérer des données dynamiques.

### 5. **Gestion des Composants Skeleton**
- Ajout de composants Skeleton pour afficher un contenu de substitution pendant le chargement des données.

### 6. **Intégration de Polices et Images**
- Utilisation de `next/font` pour intégrer des polices comme Lusitana.
- Optimisation des images avec le composant `Image` de Next.js.

### 7. **Rendu Asynchrone avec `Suspense`**
- Implémentation de `Suspense` pour gérer le rendu de composants asynchrones comme `<RevenueChart>` et `<LatestInvoices>`.

### 8. **Personnalisation Visuelle**
- Application de styles pour améliorer l’apparence de l’application.

### 9. **Finalisation**
- Nettoyage du code et test des fonctionnalités.
- Documentation du projet.

---

## Résultat Final

L’application finale est un tableau de bord fonctionnel qui :

- Affiche des données simulées pour les graphiques et les factures.
- Charge dynamiquement des composants avec des Skeleton pour une meilleure UX.
- Optimise les performances grâce à l’utilisation des fonctionnalités de Next.js.

---

## Comment Utiliser le Tutoriel

1. Suivez chaque étape du tutoriel sur [Next.js Learn](https://nextjs.org/learn/dashboard-app/getting-started).
2. Implémentez les concepts abordés dans votre propre projet.
3. Testez chaque fonctionnalité pour vous assurer qu’elle fonctionne correctement.

---

## Comment Partir le Projet depuis GitHub

1. Clonez le dépôt GitHub sur votre machine locale :
   ```bash
   git clone https://github.com/AKA29-KL/Next_Js
   cd Next_Js
   ```

2. Installez les dépendances nécessaires :
   ```bash
   npm install
   ```

3. Démarrez le serveur de développement local :
   ```bash
   npm run dev
   ```

4. Ouvrez votre navigateur et accédez à :
   ```
   http://localhost:3000
   ```

1. Suivez chaque étape du tutoriel sur [Next.js Learn](https://nextjs.org/learn/dashboard-app/getting-started).
2. Implémentez les concepts abordés dans votre propre projet.
3. Testez chaque fonctionnalité pour vous assurer qu’elle fonctionne correctement.

---

## Remarques Supplémentaires

- Si vous rencontrez des problèmes lors du tutoriel, consultez la [documentation officielle de Next.js](https://nextjs.org/docs).
- Ce tutoriel est une excellente introduction aux meilleures pratiques pour construire des applications modernes avec Next.js.

---

## Auteur

Suivi et documenté à partir du tutoriel officiel de Next.js.

