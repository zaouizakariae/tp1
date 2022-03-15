# tp1
## exercice 1
```python
 # demande a l utilisateur d entrer un nombre
 n = int(input("entrer un nombre : "))
 # si n%2 egal a 0 donc n est pair
 if n%2==0 :
    print(n," est pair")
 else :
    print(n," est impair") 
```
## exercice 2
```python
# demande a l utilisateur d entrer les deux nombres
n1 = int(input("entrer un nombre n1 : "))
n2 = int(input("entrer un nombre n2 : "))
# on compare les deux nombres pour connaitre le plus grand
if n2 > n1:
    print("les deux nombres sont ranges par ordre croissant")
    print("la difference est : ", n2 - n1)
else:
    print("les deux nombres sont ranges par ordre decroissant")
    print("la difference est : ", n1 - n2)
```
## exercice 3
```python
# on demande a l utilisateur d entrer le prix sans taxes
n = float(input("entrer le prix hors taxes : "))
# on calcule la valeur des taxes
taxes = (n*18, 6)/100
# on calcule le prix finale
pf = n+taxes
# on etablit une remise
if pf >= 1000 & pf < 2000:
    pf -= pf/100
elif pf >= 2000 & pf < 5000 :
    pf -= (pf*3) / 100
elif pf >= 5000 :
    pf -= (pf*5) / 100
print("le prix a payer est ", pf)
```
