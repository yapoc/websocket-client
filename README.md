# Installation

Pour installer ce paquet, non propagé vers `pip`, il faut : 

```
python -m venv <NOM_ENVIRONNEMENT_VIRTUEL>
source <NOM_ENVIRONNEMENT_VIRTUEL>/bin/activate
git clone https://github.com/yapoc/websocket-client.git
cd websocket-client
python setup.py build
python setup.py install
```

Et c'est magique, c'est installé!


# Utilisation & Exemples

## HTTP & Proxy 
```
import websocket
ws = websocket.WebSocket()
ws.connect("ws://example.com/websocket", http_proxy_host="proxy_host_name", http_proxy_port=3128)
```

D'autres exemples sont disponibles sur la page du projet.

# Licence et origines
  * Licence LGPL.
  * Code basé sur [ce travail](https://github.com/yapoc/websocket-client.git).
