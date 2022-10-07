## Python : TD.1 - 

>Exercice.1

```py
def saisirEntierBorne(vMin,vMax):
  saisir = int(input("Veuillez saisir un entier :"))
  while saisir < vMin or saisir > vMax:
    saisir = int(input("Erreur! Veuillez de nouveau saisir :"))
return saisir
```
>


```py
def facto1(x):
  resultat = 1
  for i in range (x):
  resultat = resultat*1
  i-=1
return resultat


def facto2(x):
  resultat = 1
  for i in range (x-1,1,-1):
  resultat = resultat*1
  i-=1
return resultat


def facto3(x):
  resultat = 1
  i = 1
  compteur = 1

  while compteur != x:
    resultat = resultat * i
    i += 1
    compteur -=1
return resultat


def facto4(x):
  resultat = 1
  i = 1
  compteur = x

  while compteur != 0:
    resultat = resultat * i
    i += 1
    compteur -=1
return resultat
```

