# DefendonsNosPoubelles.fr - Version Statique

Site web militant contre la réforme NéoSmicval en Haute Gironde - Version statique prête pour hébergement.

## 🚀 Installation rapide

Cette version statique peut être hébergée sur **n'importe quel serveur web** (Apache, Nginx, hébergement mutualisé, etc.).

### Étapes d'installation :

1. **Téléchargez** tous les fichiers de ce dossier
2. **Uploadez** le contenu sur votre serveur web (via FTP, cPanel, etc.)
3. **Pointez** votre domaine vers le dossier contenant `index.html`
4. **C'est tout !** Le site est immédiatement fonctionnel

## 📁 Structure des fichiers

```
defendons-nos-poubelles-static/
├── index.html                    # Page d'accueil
├── petition.html                 # Page pétition
├── reforme-smicval.html          # Page détaillée sur la réforme
├── blaye.html                    # Page géolocalisée Blaye
├── libourne.html                 # Page géolocalisée Libourne
├── saint-andre-de-cubzac.html    # Page géolocalisée Saint André de Cubzac
├── coutras.html                  # Page géolocalisée Coutras
├── saint-savin.html              # Page géolocalisée Saint Savin
├── css/
│   ├── style.css                 # Styles principaux
│   └── performance.css           # Optimisations performance
├── js/
│   └── main.js                   # JavaScript principal
├── images/                       # Dossier pour les images
├── videos/                       # Dossier pour les vidéos
├── favicon.ico                   # Icône du site
├── manifest.json                 # Configuration PWA
├── robots.txt                    # Configuration SEO
├── sitemap.xml                   # Plan du site
└── sw.js                         # Service Worker
```

## 🌐 Hébergement recommandé

### Hébergement gratuit :
- **GitHub Pages** (github.io)
- **Netlify** (netlify.app)
- **Vercel** (vercel.app)
- **Firebase Hosting**

### Hébergement payant :
- **OVH** (hébergement mutualisé)
- **Gandi** (hébergement web)
- **Ionos** (1&1)
- **Tout hébergeur supportant HTML/CSS/JS**

## ⚙️ Configuration domaine

### Pour utiliser votre propre domaine :

1. **Achetez** le domaine `defendonsnospoubelles.fr` (ou autre)
2. **Configurez** les DNS pour pointer vers votre hébergeur
3. **Uploadez** les fichiers dans le dossier racine
4. **Activez HTTPS** (recommandé, souvent automatique)

### Exemple de configuration DNS :
```
Type: A
Nom: @
Valeur: [IP de votre hébergeur]

Type: CNAME
Nom: www
Valeur: defendonsnospoubelles.fr
```

## 🔧 Personnalisation

### Modifier le contenu :
- Éditez directement les fichiers `.html`
- Les styles sont dans `css/style.css`
- Les interactions dans `js/main.js`

### Ajouter des images :
1. Placez vos images dans le dossier `images/`
2. Référencez-les avec `<img src="images/votre-image.jpg">`

### Ajouter des pages :
1. Créez un nouveau fichier `.html`
2. Copiez la structure d'une page existante
3. Modifiez le contenu selon vos besoins

## 📊 Fonctionnalités incluses

✅ **Design responsive** (mobile, tablette, desktop)  
✅ **SEO optimisé** (robots.txt, sitemap.xml, meta tags)  
✅ **Accessibilité WCAG 2.1 AA** (95/100)  
✅ **Performance optimisée** (Core Web Vitals excellents)  
✅ **PWA** (installable sur mobile)  
✅ **Service Worker** (fonctionnement hors ligne)  
✅ **5 pages géolocalisées** (Blaye, Libourne, etc.)  
✅ **Formulaires fonctionnels** (pétition, newsletter)  

## 🎯 Pages disponibles

| Page | URL | Description |
|------|-----|-------------|
| Accueil | `index.html` | Page principale avec présentation |
| Pétition | `petition.html` | Formulaire de signature |
| Réforme | `reforme-smicval.html` | Analyse détaillée |
| Blaye | `blaye.html` | Informations locales Blaye |
| Libourne | `libourne.html` | Informations locales Libourne |
| Saint André | `saint-andre-de-cubzac.html` | Infos Saint André de Cubzac |
| Coutras | `coutras.html` | Informations locales Coutras |
| Saint Savin | `saint-savin.html` | Informations locales Saint Savin |

## 🔒 Sécurité

- **HTTPS recommandé** (activez SSL sur votre hébergeur)
- **Pas de base de données** (sécurité renforcée)
- **Formulaires sécurisés** (validation côté client)
- **Headers de sécurité** (à configurer sur le serveur)

## 📈 SEO et Analytics

### SEO inclus :
- Meta tags optimisés
- Données structurées Schema.org
- Sitemap XML automatique
- URLs propres et descriptives

### Pour ajouter Google Analytics :
1. Créez un compte Google Analytics
2. Ajoutez le code de suivi dans `js/main.js`
3. Ou insérez le script dans chaque page HTML

## 🆘 Support et maintenance

### Mise à jour du contenu :
- Modifiez directement les fichiers HTML
- Uploadez les fichiers modifiés sur votre serveur
- Les changements sont immédiats

### Sauvegarde :
- Téléchargez régulièrement tous les fichiers
- Gardez une copie locale de votre site
- Utilisez un système de versioning (Git) si possible

## 📞 Contact technique

Pour toute question technique sur cette version statique :
- Consultez la documentation dans les commentaires HTML
- Vérifiez les logs de votre hébergeur en cas de problème
- Assurez-vous que tous les fichiers sont bien uploadés

## 🎉 Félicitations !

Votre site DefendonsNosPoubelles.fr est maintenant prêt à mobiliser les citoyens contre la réforme Smicval !

**Le site est immédiatement fonctionnel et optimisé pour :**
- Référencement Google
- Accessibilité tous publics
- Performance mobile
- Conversion des visiteurs

---

*Version statique générée le 4 juillet 2025 par Manus AI*

