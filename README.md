# H3
viikko 3 tehtävät

c) Näytä omalla salt-varastollasi esimerkit komennoista ‘git log’, ‘git diff’ ja ‘git blame’. Selitä tulokset.

Tein tehtävän http://terokarvinen.com/2016/publish-your-project-with-github ohjeiden mukaisesti.

Annoin komennon git log /srv/salt/H3-kansiossa ja otin kuvan yhdestä merkinnästä. Commit kohta on sillä kertaa tallennettujen muustosten tiiviste. Author kertoo tekijän tiedot ja date ajankohdan.

```
$ git log 
```  
![githubkuva](https://user-images.githubusercontent.com/49511043/56204408-09d33e80-6050-11e9-8d14-93b8e68c51ad.jpg)  
  
Seuraavaksi annoin komennon git diff samassa kansiossa. Git diff otsikko kertoo, että eroja tarkastellaan näiden välillä. Index kertoo, että kyseessä on tavallinen tiedosto.

```
$ git diff
$ git diff ee237967ac043434345f91681c37b68bffb2f4da
```





 








