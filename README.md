# data_alto

# DO IT 

Workflow :
  - faire les vérifications (voir htr united)
  - Compresser au maximum les xml pour reduire la taille ( find . -name "*.xml" -type f -exec xmllint --noblanks {} --output {}.min \; -exec mv {}.min {} \;) -> Doit s'appliquer quand on push seulement sur les fichiers modifiés ou ajoutés
