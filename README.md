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
![githubkuva2](https://user-images.githubusercontent.com/49511043/56206140-56207d80-6054-11e9-9761-663fa78d5d2e.jpg)  

Viimeisenä laitoin komennon Git blame. Komennolla voidaan selvittää koska riveille on tehty muutoksia. Raportista katsoin rivit 1-20. Toisella rivillä ensimmäinen teksti tarkoittaa Committia ja suluista löytyy muokkaaja, päiväys, kellonaika, aikavyöhyke ja rivinumero.  

```
$ git blame -L 1,20 README.md
```  

![githubkuva3](https://user-images.githubusercontent.com/49511043/56210019-9a644b80-605d-11e9-8f35-ae7a08b8e7eb.jpg)  
  
e) Tee tyhmä muutos gittiin, älä tee commit:tia. Tuhoa huonot muutokset ‘git reset –hard’. Huomaa, että tässä toiminnossa ei ole peruutusnappia.  

Loin uuden kansion ja otin kuvan tästä. Tämän jälkeen koitin tuhota kansiota "git reset --hard" komennolla, mutta jostain syystä kansio löytyy vielä.

```
$ sudoedit uusikansio.md  
$ ls  
$ sudo git reset --hard
```  
![githubkuva4](https://user-images.githubusercontent.com/49511043/56211232-211a2800-6060-11e9-81f9-7448d9a47825.jpg)![githubkuva5](https://user-images.githubusercontent.com/49511043/56212253-545db680-6062-11e9-9913-d475f2b372b2.jpg)











 








