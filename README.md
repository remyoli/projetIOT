# projetIOT
projet IOT derniere année irc

Ubidots: IOTProject5IRC


Partie Arduino via une virtualbox

Si la virtualbox ne détecte pas l'arduino => redémarrez
Si la virtualbox détecte l'arduino mais montre l'erreur suivante lors du téléversement:

can't open device "/dev/ttyACM0"

Tapez:

$ sudo chmod a+rw /dev/ttyACM0
$ sudo udevadm trigger
