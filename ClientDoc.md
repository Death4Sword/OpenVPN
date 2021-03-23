## Installation d'OpenVPN côté client

## Réseau Privé Virtuel ou VPN :
Le VPN ou Virtual Private Network est un réseau informatique, nous permettant de créer un lien direct entre des ordinateurs distants. Isolants leurs échanges du reste du trafic. 
Protégeant les données via un réseau crypté.
OpenVPN est un VPN TLS/SSL. Cette technologie utilise des certificats afin de chiffrer le trafic entre le serveur et les clients.

## Windows 10

## Installation :

- Téléchargez OpenVPN avec le lien ci-joint : https://openvpn.net/community-downloads/
- Sélectionnez le "WINDOWS 32/64-BIT MSI INSTALLER" (32 ou 64 en fonction de votre ordinateur)
- Installez sans option particulière
- Lancez l'application OpenVPN

## Configuration d'OpenVPN :

- Une fois la partie installation finie, cliquez en bas à droite dans vos icônes cachées et faite clique-droit sur "OpenVPN GUI"
- Cliquez ensuite sur "importer un fichier"
- Sélectionner le fichier ayant l'extension **.ovpn** que nous vous fournissons
- Glissez ensuite tous les fichiers fournis (ca, client, dh-4096, ta.key ainsi que client.key) dans le répertoire OpenVPN situé à "C:/Users/YouName/OpenVPN/config/client"
- Retournez dans vos icônes cachées et cette fois-ci cliquez sur "Connecter"
- Vous êtes désormais connecter à votre VPN, vos échanges sont maintenant sécurisés
