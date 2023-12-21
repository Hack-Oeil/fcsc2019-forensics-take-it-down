# FCSC 2019 - Take It Down

Un botnet vient d’être démantelé ! Les communications avec le C2 sont détournées avec un Sinkhole depuis lequel des captures réseau sont faites. Malheureusement, l’analyste en charge de cette investigation n’a pas réussi à décoder ces communications… Il a tout de même mis en place un honeypot et a réussi à tromper ce botnet qui s’attaque principalement à des Raspberry PI exposés sur Internet avec le service SSH activé et mot de passe par défaut.

Votre mission, retrouver et décoder les données contenues dans la capture réseau pour identifier la victime à l’aide du script client [client.py](client.py).

[sinkhole_capture.pcap](sinkhole_capture.pcap)


Note : Cette épreuve avait été proposée lors de la finale du FCSC 2019.

-----------

Auteur : alx

Origine : [Take It Down](https://hackropole.fr/fr/challenges/forensics/fcsc2019-forensics-take-it-down/)



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2019-forensics-take-it-down.git

> cd fcsc2019-forensics-take-it-down


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2019-forensics-take-it-down/