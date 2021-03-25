## Installation d'OpenVPN côté client

## Réseau Privé Virtuel ou VPN :
Le VPN ou Virtual Private Network est un réseau informatique, nous permettant de créer un lien direct entre des ordinateurs distants. Isolants leurs échanges du reste du trafic. 
Protégeant les données via un réseau crypté.
OpenVPN est un VPN TLS/SSL. Cette technologie utilise des certificats afin de chiffrer le trafic entre le serveur et les clients.


<br>


## Windows 10

## Installation :

- Téléchargez OpenVPN avec le lien ci-joint : https://openvpn.net/community-downloads/
- Sélectionnez le "WINDOWS 32/64-BIT MSI INSTALLER" (32 ou 64 en fonction de votre ordinateur)
- Installez sans option particulière
- Lancez l'application OpenVPN


<br>


## Configuration d'OpenVPN :
- Une fois la partie installation finie, téléchargez le dossier **"client.zip"** que nous vous fournissons, glissez le dans le répertoire OpenVPN situé à :
  **"C:/Users/YourName/OpenVPN/config/client"**
- Faites clique-droit dessus, puis "Extraire ici"
- Dès que cela est fait assurez vous, que les fichiers "ca, client, client.key, dh-4096.pem et ta.key" soient bien présent.
- Une fois votre vérification faite, cliquez sur la petite flêche en bas à droite de votre écran, qui vous montreras les icônes cachées.
- Effectuez un clique-droit sur "l'écran avec le cadenas" (OpenVPN GUI) et cliquez sur "Connecter"
- Vous êtes désormais connecter à votre VPN, vos échanges sont maintenant sécurisés