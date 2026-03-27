# lab_python_upd

mon nom est NANA WANDA FRANCK
ceci est le Laboratoire – Introduction aux sockets


La différence vient du fait que, en UTF-8, chaque caractère peut être encodé sur plusieurs octets. Par exemple, un caractère accentué ou un emoji va prendre plus d’un octet. Donc, la longueur en bytes (len(b)) sera plus grande que la longueur en caractères (len(s)), qui elle compte juste les caractères indépendamment de leur taille. En résumé, le texte est plus compact en nombre de caractères, mais il prend plus d’octets en mémoire.


les sockets UDP envoient toujours des données brutes, c’est-à-dire des bytes, parce que le réseau ne connaît pas la notion de texte.


les deux font référence au calcul du hachage, mais ils renvoient des formats différents. La méthode digest() retourne le hachage sous forme de bytes bruts, alors que hexdigest() retourne le hachage sous forme de chaîne hexadécimale lisible. Donc, si on veut stocker ou afficher le hachage, on utilise hexdigest(), mais si on a besoin de manipuler les bytes bruts (par exemple pour un stockage binaire), on utilise digest().


un nonce, c’est comme un petit nombre aléatoire qu’on utilise une seule fois dans un échange. Son but, c’est de garantir que chaque interaction est unique. En empêchant les messages de se répéter, il évite les attaques par rejeu, où un attaquant pourrait simplement réenvoyer un vieux message pour tromper le système. Donc, le nonce apporte une garantie d’unicité et de fraîcheur au message.
