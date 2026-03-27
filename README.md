# lab_python_upd

mon nom est NANA WANDA FRANCK
ceci est le Laboratoire – Introduction aux sockets


La différence vient du fait que, en UTF-8, chaque caractère peut être encodé sur plusieurs octets. Par exemple, un caractère accentué ou un emoji va prendre plus d’un octet. Donc, la longueur en bytes (len(b)) sera plus grande que la longueur en caractères (len(s)), qui elle compte juste les caractères indépendamment de leur taille. En résumé, le texte est plus compact en nombre de caractères, mais il prend plus d’octets en mémoire.


les sockets UDP envoient toujours des données brutes, c’est-à-dire des bytes, parce que le réseau ne connaît pas la notion de texte.
