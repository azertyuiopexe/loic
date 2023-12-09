INFO
Low Orbit Ion Cannon (LOIC) est un outil de contrainte réseau open source, écrit en C#. LOIC est basé sur le projet LOIC de Praetox à https://sourceforge.net/projects/loic/.

DÉMENTI
LOIC est uniquement destiné à des fins éducatives, destiné à aider les propriétaires de serveurs à développer une attitude de « défense contre les pirates ». Cet outil est livré sans aucune garantie.

Vous ne pouvez pas utiliser ce logiciel à des fins illégales ou contraires à l’éthique. Cela inclut les activités qui donnent lieu à une responsabilité pénale ou civile.

En aucun cas, le concédant ne pourra être tenu responsable des activités ou des méfaits du titulaire de la licence.

COMMENT EXÉCUTER SOUS WINDOWS
PROCUREZ-VOUS LES BINAIRES !

Nécessite Microsoft .NET Framework 3.5 Service Pack 1, disponible à l’adresse suivante : http://www.microsoft.com/downloads/en/details.aspx?FamilyID=ab99342f-5d1a-413d-8319-81da479ab0d7&displaylang=en

COMMENT FONCTIONNER SOUS LINUX / MACOSX
Exécutez des binaires de débogage avec Mono ou Wine. Lisez le wiki à https://github.com/NewEraCracker/LOIC/wiki/_pages pour obtenir des instructions mises à jour.

ESPRIT DE RUCHE/MODE CACHÉ
Le mode HIVEMIND connectera votre client à un serveur IRC afin qu’il puisse être contrôlé à distance. Considérez cela comme un botnet volontaire. S’il vous plaît être conscient que votre client peut potentiellement être fait pour faire des choses coquines.

Remarque : Il ne permet PAS l’administration à distance de votre machine ; il fournit simplement le contrôle de LOIC lui-même.

Si vous voulez démarrer en mode Hivemind, exécutez quelque chose comme ceci :

	LOIC.exe /hivemind irc.server.address
qui se connectera à irc://irc.server.adress:6667/loic

Vous pouvez également spécifier un port et un canal :

	LOIC.exe /hivemind irc.server.address 1234 #secret
qui se connectera à irc://irc.server.adress:1234/secret

Afin d’exécuter le mode Hivemind Hidden (Esprit de ruche), exécutez quelque chose comme ceci :

	LOIC.exe /hidden /hivemind irc.server.address
qui se connectera à irc://irc.server.adress:6667/loic sans aucune interface graphique visible.

CONTRÔLE DE LA LOIC À PARTIR D’IRC
En tant qu’OP, Admin ou Propriétaire, définissez le sujet de la chaîne ou envoyez un message tel que le suivant :

	!lazor targetip=127.0.0.1 message=test_test port=80 method=tcp wait=false random=true
Pour lancer une attaque, tapez :

	!lazor start
ou ajoutez « start » à la fin de la rubrique :

	!lazor targetip=127.0.0.1 message=test_test port=80 method=tcp wait=false random=true start
Pour réinitialiser les options de LOIC à leurs valeurs par défaut :

	!lazor default
Pour arrêter une attaque :

	!lazor stop
et assurez-vous de supprimer « start » de la FIN du sujet, s’il existe également.

Jetez un coup d’œil au code source pour plus de détails.

