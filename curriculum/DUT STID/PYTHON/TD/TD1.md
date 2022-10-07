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


```py
def afficher(x):
  print(x)
```


```py
x = saisirEntierBorne(2,10)

menu = True

while menu : 
  print("1/facto1 \n2/facto2  \n3/facto3   \n4/facto4 \n5/quitter \n")
  choix = int(input("veuillez choisir votre menu :"))
  
  if choix == 1 :
    afficher(facto1(x))
  elif choix == 2 :
    affichier(facto2(x))
  elif choix == 3 :
    affichier(facto3(x))
  elif choix == 4 :
    affichier(facto4(x))
  elif choix == 5:
    print("Quitter")
    menu=False
  else:
    print("Erreur!")

```
