
1. **build**
docker build -t mycvbhr .
2. **run avec un volume.**
docker run -it --rm -p 8000:8000 -v chemin_du_projet\cvkalthoum\src:/app/src mycvbhr
(docker run -it --rm -p 8000:8000 -v chemin_du_projet\cvkalthoum\src:/app/src mycvbhr)
'localhost:8000'
=> En fait a chaque modification dans le code pas besoin de faire un 'run' une autre fois, une fois que vous avez fait un 'CTRL + s' le changement est fait automatiquement
3. **Site !**
le lien du site 'nawelbhr.netlify.app'







