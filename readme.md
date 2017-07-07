Cloner un d�p�t existant
Si vous souhaitez obtenir une copie d'un d�p�t Git existant � par exemple, un projet auquel vous aimeriez contribuer � la commande dont vous avez besoin s'appelle git clone. 
Si vous �tes familier avec d'autres syst�mes de gestion de version tels que Subversion, 
vous noterez que la commande est clone et non checkout. 
C'est une distinction importante � Git re�oit une copie de quasiment toutes les donn�es dont le serveur dispose. 
Toutes les versions de tous les fichiers pour l'historique du projet sont t�l�charg�es quand vous lancez git clone. 
En fait, si le disque du serveur se corrompt, vous pouvez utiliser n'importe quel clone pour remettre le serveur dans l'�tat o� il �tait au moment du clonage 
(vous pourriez perdre quelques param�tres du serveur, mais toutes les donn�es sous gestion de version seraient r�cup�r�es � cf. chapitre 4 pour de plus amples d�tails).

Vous clonez un d�p�t avec git clone [url]. 
Par exemple, si vous voulez cloner la biblioth�que Git Ruby appel�e Grit, vous pouvez le faire de la mani�re suivante :

$ git clone git://github.com/schacon/grit.git


https://git-scm.com/book/fr/v1/Les-bases-de-Git-D%C3%A9marrer-un-d%C3%A9p%C3%B4t-Git