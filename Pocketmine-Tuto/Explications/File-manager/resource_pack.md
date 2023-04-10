# Comment mettre un pack de texture sur un serveur pocketmine

__Un pack de texture dans les grand mot c'est' un changement de texture... en gros tu prend une épée en fer bas tu modifie la texture pour en faire un catus__

# Ou aller?

__Une fois que vous avez votre pack de texture rendez-vous dans le fichier (resource_pack) et exporté le fichier en .zip ne le déarchivée pas__

__Ensuite allez dans le fichier (resource_pack.yml) regardez la config__ 

# Config du fichier 
#This configuration file controls global resources used on your PocketMine-MP server.

#Choose whether players must use your chosen resource packs to join the server.
#NOTE: This will do nothing if there are no resource packs in the stack below.
force_resources: false
resource_stack:
  #Resource packs here are applied from bottom to top. This means that resources in higher packs will override those in lower packs.
  #Entries here must indicate the filename of the resource pack.
  #Example
  # - natural.zip
  # - vanilla.zip
  #If you want to force clients to use vanilla resources, you must place a vanilla resource pack in your resources folder and add it to the stack here.
  #To specify a resource encryption key, put the key in the <resource>.key file alongside the resource pack. Example: vanilla.zip.key
---

# Comment activée le pack ?

__La ou il y est écrit (vanilla.zip), juste en dessous écrivez par exemple (- TutoPack.zip) et faite sauvegarder__

__Le (force_resources: fait en sorte que quand les joueur rejoint le serveur il sont obligé de downloads le pack)__

# Information

__true = Vrai__

__False = Faux__

# Information

__Si vous faite des texture avec beaucoup trop de détails il ce peut que les gens on de la difficulté a télécharger le pack meme a avoir des perte de FPS sur votre serveur__

__Taille de texture a ne pas dépasser = 128x128__
