> Lien utile : [Dark Reader](https://github.com/darkreader/darkreader)

# Extensions particulières
- CyberGhost, [Foxy Proxy](https://github.com/foxyproxy/firefox-extension)

CyberGhost et Foxy Proxy sont utilisés afin de rediriger les requêtes HTTP(S) pour qu'elles paraissent venir d'un serveur tiers et non pas du réseau initial.

CyberGhost se base sur un modèle de type VPN (Virtual Private Network). Il permet, au delà des autres fonctionnalités, de rendre les blocages géographiques caduc. Typiquement, vous pouvez accéder au média de la BBC sans être recalé par votre localisation en France.

Tandis que Foxy Proxy, comme son nom l'indique, se base sur un modèle proxy/ client. Ici, le proxy permet deux choses particulièrement intéressantes: délocaliser sa connection (comme un VPN) et de consulter/modifier/refuser des requêtes (en partant du principe que vous avez la main sur ledit proxy). En utilisation, on peut utiliser BurpSuite nous permettant d'effectuer les actions citées précédemment.

- HTTPS Everywhere

HTTPS Everywhere est une extension permettant de forcer l'utilisation des sites dans leurs versions HTTPS, avec chiffrement TLS donc.

- Katalon Recorder

Katalon Recorder est une extension permettant entre-autre d'automatiser des tâches répétitives d'une page web. Concrètement, nous pouvons injecter de la donnée dans un formulaire de manière automatique.

- wappalyzer

Wappalyzer est une extension spécifique à un cas d'usage: l'analyse d'un site web. Cette extension permet de déterminer quel serveur backend est utilisé ainsi que, dans certains cas, les modèles frontend utilisés. Il prends en compte le serveur web, si un CMS est utilisé, et si oui le template mis en place, etc...

## Cas d'utilisation (avec code)
- Surfer en toute sécurité
- Chiffrement des communications (forcer le SSL)
- Automatisation de tâches répétitives
- Analyse de sites (version, technos), extension qu'on a utilisé l'année dernière

TP 2 : Création d'une méthode pour forger une requête HTTP (sujet à définir)