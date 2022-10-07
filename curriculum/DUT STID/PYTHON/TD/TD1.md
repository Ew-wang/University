## Python : TD.1 - 

>Exercice.1

```py
def saisirEntierBorne(vMin,vMax):
  saisir = int(input("Veuillez saisir un entier :"))
  while saisir < vMin or saisir > vMax:
    saisir = int(input("Erreur! Veuillez de nouveau saisir :"))
return saisir
```

