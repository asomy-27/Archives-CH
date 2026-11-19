ARCHIVES CH — PWA pour Samsung Galaxy S22 Ultra

Installation :
1. Décompresser l'archive.
2. Mettre le contenu du dossier archives-ch (index.html, app.js, data.js, sw.js, manifest.webmanifest, icons/) sur un hébergement statique HTTPS (par exemple GitHub Pages, Netlify ou Cloudflare Pages). Ne pas ouvrir index.html directement depuis les fichiers du téléphone : l'installation PWA et le mode hors ligne exigent HTTPS ou localhost.
3. Sur le Samsung, ouvrir l'adresse HTTPS dans Chrome.
4. Menu ⋮ > Ajouter à l'écran d'accueil > Installer (le libellé peut varier).
5. Ouvrir une première fois en ligne et attendre le chargement; le service worker met en cache tous les fichiers. L'application fonctionne ensuite hors ligne.

Confidentialité : aucun serveur d'application, aucun suivi, aucune donnée personnelle envoyée. Les fichiers statiques sont téléchargés lors de la visite initiale.
Mise à jour : modifier les fichiers et incrémenter le nom CACHE dans sw.js pour forcer la mise à jour du cache.
Attention : les durées sont indicatives, non des conseils juridiques. La date de destruction est volontairement prudente et simplifiée.
