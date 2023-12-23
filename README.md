#savoir si un fichier python existe dans le repertoire

from pathlib import Path
Path("C:/Program Files(x86)/fichier.txt").exist()

#si le programme renvoi false donc le fichier n'existe pas.


