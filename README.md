[**Cours du jeudi 2 septembre**](https://mybinder.org/v2/gh/fortierq/mp2i-binder/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Ffortierq%252Fmp2i-2021%26urlpath%3Dlab%252Ftree%252Fmp2i-2021%252F%252F1_OCaml/1_variables.ipynb%26branch%3Dmain)

# Utiliser Jupyter

## Binder [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fortierq/mp2i-binder/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Ffortierq%252Fmp2i-2021%26urlpath%3Dlab%252Ftree%252Fmp2i-2021%252F%26branch%3Dmain)  
**Attention : les données ne sont pas sauvegardées sur Binder. Pensez à télécharger (File -> Download) votre travail quand vous avez terminé.**

## Optionnel et plus compliqué : Docker
Avec Docker, vous pouvez lancer Jupyter avec tous les outils installés en local. Jupyter est alors plus rapide à lancer et n'a pas besoin d'Internet, mais l'installation est un peu compliquée.
1. Télécharger Docker desktop : https://www.docker.com/get-started (download for Windows si vous êtes sous Windows).
2. Installer Docker desktop.
3. Lancer Docker desktop.
4. Ouvrez un terminal (sous Windows : Windows+R, taper "cmd" puis entrée.
5. Tapez `docker run -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan/work qfortier/mp2i:2.0.0`.
6. Si tout se passe bien, l'image Docker contenant Jupyter se télécharge (~ 5Go, ça prend du temps).
7. Quand l'image est lancée, un message devrait apparaître avec une url : copier-coller la dernière adresse URL pour utiliser Jupyter.
```
To access the server, open this file in a browser:
    file:///home/jovyan/.local/share/jupyter/runtime/jpserver-8-open.html
Or copy and paste one of these URLs:
    http://9e0e7a819898:8888/lab?token=3c2893614dbd1935d3b63fd06f6975c8641a52c7e51e0321
 or http://127.0.0.1:8888/lab?token=3c2893614dbd1935d3b63fd06f6975c8641a52c7e51e0321
```

# Poser des questions

- Serveur discord pour l'informatique MP2I : [![Discord](https://img.shields.io/discord/591914197219016707.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/E7abJNbZ)
  
- Onglet Discussions sur GitHub.

# Références pour l'informatique

- MP2I :
    - [Programme officiel MP2I-MPI](https://cache.media.education.gouv.fr/file/SPE1-MEN-MESRI-4-2-2021/64/6/spe777_annexe_1373646.pdf)  
    - https://marcdefalco.github.io/

- OCaml :
    - https://cs3110.github.io/textbook/cover.html

- Algorithmique :
    - https://jeffe.cs.illinois.edu/teaching/algorithms/
