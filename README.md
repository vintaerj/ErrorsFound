# ErrorsFound
All my errors i've met since i've been programming

1. Proxy variable environment
  * unset to remove variable : like unset http_proxy
  * error with curl it was the variable proxy, i've deleted it with unset command and it has worked perfectly.
  
2. Problème avec luasocket et nc , les packets n'arrivé pas au serveur.
  * il fallait mettre l'option "-u" pour envoyer en udp, car par default c'est tcp, donc le serveur ne capturais pas les paquet car il était en udp.
  
  
3. Problème de proxy encore sur linux. Je recevais une erreur 403 , c'était le proxy qui répondait.
solution : no_proxy=localhost pour dire au proxy d'ignorer localhost.
