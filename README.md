🏋️‍♂️ Will Fitness – Site web de réservation pour salle de sport

Site web vitrine moderne et responsive pour une salle de sport située à Abidjan (Côte d’Ivoire), avec présentation des services, avis clients, réservation en ligne et envoi d’emails via EmailJS.

🚀 Fonctionnalités
🎨 Design sportif moderne et immersif
📱 100 % responsive (mobile, tablette, desktop)
🖼️ Slider d’images automatique sur la page d’accueil
💪 Présentation détaillée des services sportifs
⭐ Section avis clients
📅 Formulaire de réservation fonctionnel (sans paiement)
📩 Envoi automatique d’email via EmailJS (Gmail)
📍 Intégration Google Maps
📞 Boutons WhatsApp et appel direct
🔍 SEO local de base (Abidjan)

🛠️ Technologies utilisées

HTML5
CSS3 (animations, responsive design)
JavaScript (Vanilla)
EmailJS (envoi d’emails côté client)
Google Maps Embed

📂 Structure du projet
will-fitness/
│
├── index.html
├── images/
│   ├── img1.jpg
│   ├── img2.jpg
│   ├── img3.jpg
│   ├── img4.jpg
│   └── img5.jpg
└── README.md

⚙️ Installation & utilisation
1️⃣ Cloner ou télécharger le projet
git clone https://github.com/ton-compte/will-fitness.git


Ou télécharge le projet en ZIP.

2️⃣ Ajouter les images

Crée un dossier images/ à la racine du projet

Ajoute tes images de fond :

slide1.jpg
slide2.jpg
slide3.jpg
slide4.jpg
slide5.jpg

3️⃣ Configurer EmailJS

Crée un compte sur https://www.emailjs.com
Ajoute un service email (Gmail recommandé)
Crée un template d’email avec les variables suivantes :

name
email
phone
service
date
time


Dans index.html, remplace :

emailjs.init("TON_PUBLIC_KEY");
emailjs.send("TON_SERVICE_ID", "TON_TEMPLATE_ID", formData);


Par tes vraies clés EmailJS :

emailjs.init("PUBLIC_KEY");
emailjs.send("SERVICE_ID", "TEMPLATE_ID", formData);


⚠️ Ne jamais utiliser la clé privée dans le code HTML.

🗺️ Configuration Google Maps

Remplace dans l’iframe Google Maps :

src="https://www.google.com/maps/embed?pb=TON_EMBED_MAP"


Par ton lien Google Maps Embed réel.

📞 Personnalisation des contacts

Dans le footer :

Remplace le numéro WhatsApp :

https://wa.me/225XXXXXXXXX


Remplace le numéro d’appel :

tel:+225XXXXXXXXX

🌍 Mise en ligne

Le site peut être hébergé sur :

Hostinger
Netlify
Vercel
GitHub Pages

👉 Il suffit d’uploader index.html et le dossier images/.

🔐 Sécurité

Aucune donnée n’est stockée en base de données
Les emails sont envoyés via EmailJS
Aucune clé privée exposée côté client

📌 Améliorations possibles

Ajout de paiement en ligne (Stripe / Mobile Money)
Tableau de bord admin
Multi-langues
Notifications WhatsApp API
Authentification utilisateurs

👤 Auteur

Will Fitness
Salle de sport – Abidjan, Côte d’Ivoire

Développé par : Aboussou emmanuel

📄 Licence

Projet libre d’utilisation pour usage personnel ou commercial.
