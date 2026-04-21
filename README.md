# ✨ K-PhotoCard Manager

> **Gère, organise et suis ta collection de photocards K-Pop comme un(e) pro.**  
> Une application web légère, moderne et 100% offline, conçue spécialement pour les fans de K-Pop.
> 
> https://brunimaro.github.io/k-photocard-manager/

## ✨ Fonctionnalités

| Catégorie | Détails |
|---|---|
| 🏠 **Dashboard** | Statistiques en temps réel : total, collectées, wishlist, à échanger, groupes, legendary |
| 💎 **Collection** | Ajout, modification, suppression avec formulaire intuitif et prévisualisation d'image |
| 🔍 **Filtres & Recherche** | Recherche textuelle + filtres par groupe, membre, statut, rareté et tri personnalisé |
| 📂 **Catégories** | Organisation automatique par groupe et par statut (Collectée, Wishlist, Trade, Dupliquée) |
| 💫 **Wishlist & Trade** | Pages dédiées pour tracker les photocards manquantes et celles à échanger |
| 💾 **Export/Import** | Sauvegarde complète en JSON pour ne jamais perdre ta collection |
| 📱 **Responsive** | Interface adaptative (desktop, tablette, mobile) avec menu latéral rétractable |
| 🎨 **UI/UX K-Pop** | Glassmorphism, gradients rose/violet, animations fluides et effets ✨ interactifs |

## 🛠️ Technologies Utilisées

- **HTML5** – Structure sémantique & accessible
- **CSS3** – Variables, Flexbox/Grid, Glassmorphism, Animations CSS, Media Queries
- **JavaScript (ES6+)** – Logique applicative, DOM manipulation, LocalStorage
- **Google Fonts** – `Poppins` & `Quicksand`
- **Aucun framework** – 100% vanilla, léger et rapide

## 🚀 Installation & Utilisation

Aucune installation complexe ! L'application fonctionne entièrement côté client.

1. **Télécharge ou clone** ce dépôt :
   ```bash
   git clone https://github.com/ton-username/k-photocard-manager.git
   cd k-photocard-manager
   ```
2. **Ouvre** le fichier `index.html` dans ton navigateur préféré (Chrome, Firefox, Edge, Safari).
3. **Commence à ajouter** tes photocards via le bouton `✨ Ajouter une Photocard`.

> ⚠️ **Note** : Les données sont stockées dans le `localStorage` de ton navigateur. Pense à exporter régulièrement ta collection via le bouton `💾 Exporter` dans la sidebar.

## 💾 Sauvegarde & Portabilité

| Action | Comment |
|---|---|
| **Exporter** | Clique sur `💾 Exporter` → Télécharge un fichier `.json` |
| **Importer** | Clique sur `📥 Importer` → Sélectionne ton fichier `.json` |
| **Réinitialiser** | Efface les données de navigation ou utilise `localStorage.clear()` dans la console |

## 🗺️ Roadmap

- [ ] Upload d'images locales (drag & drop / file input)
- [ ] Thèmes personnalisables (Light/Dark, couleurs des groups)
- [ ] Suivi des trades (historique, contacts, dates d'échange)
- [ ] Import automatique via API (Discogs, Melon, etc.)
- [ ] Synchronisation cloud (Firebase/Supabase)
- [ ] Mode hors ligne (PWA)

## 🤝 Contribution

Les contributions sont les bienvenues ! 🌟

1. Fork le projet
2. Crée ta branche (`git checkout -b feature/ta-super-feature`)
3. Commit tes changements (`git commit -m '✨ Ajoute une super fonctionnalité'`)
4. Push vers la branche (`git push origin feature/ta-super-feature`)
5. Ouvre une Pull Request

Merci de respecter le style de code existant et d'ajouter des commentaires clairs.

## 📜 Licence

Ce projet est distribué sous la licence **MIT**. Voir le fichier `LICENSE` pour plus de détails.
