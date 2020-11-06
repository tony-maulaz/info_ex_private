Transformer 5 en binaire :

Transformer 8 en binaire :

Quel est la valeur de `a` pour chaque ligne : 

```C
int a = 5 | (1 << 1);
a = 5 & (1 << 2);
a = 3 & 2 == 2;
a = (8 & (1 << 3)) == 0x8 && 3 & 2 == 2;
```

Quel est l’affichage du code suivant :
```C
int i = 0 ;
while( i++ < 10 ){}
  printf("i=%d", i);
}
```

Remplir les `printf` suivants pour que l’affichage corresponde à celui-ci-dessous
```C
int a=-1;
double b=100.123, c=-4.5;
printf(...);
printf(...);
printf(...);
```

```BASH
|  -1
| 100.123 
|  -4.5 
```

Dans un programme, on reçoit la chaine de caractère suivant : `N=XXX/QXXX`
Dans cette chaine, les `XXX` sont des nombres entiers que l’on veut récupérer.
```C
int nbr = sscanf( la_chaine, "…", &val1, &val2 )
```

Que faut-il écrire dans le `sscanf` :


Quel est l’affichage du programme suivant :

```C
int a = 0, b = 100;
if( a > b || true ){
    printf("Hello\n");
}
printf("End\n");
```

Quel est l’affichage du programme suivant :

```C
int a = 0, b = 100;
if( a == b && b > 10 )
    printf("Cas 1\n");
else if( a == 3 || b > 34 && a > 0 )
    printf("Cas 2\n");
else
    printf("Cas 3\n");
```

Quel est l’affichage de :

```C
a = 3; 
b = 6;
printf("Val = %d", a > b ? a : b);
```

Ecrire une boucle `for` qui écrit les caractères de `R` à `C` séparé par un `–`

```BASH
R-Q-P-O…
```

Donner le type du resultat des calculs suivant:
```C
int i;
double d;
bool b;

// Exemple
i * i; // int

i * d; 
b && i;
d > i;
!b;
```
