// Still not finished

## Hello, World!

Il est l'heure pour vous d'écrire votre tout premier bout de code en C, et nous allons suivre une tradition millénaire (au moins) parmi les programmeurs: commencer par un Hello world.

Cela consiste à écrire un programme dont le seul objectif est d'afficher à l'utilisateur les mots "Hello, World!", pour signifier nos débuts dans un nouveau langage.

### Le code
La première étapes est de créer un fichier `hello.c` et de l'ouvrir dans un éditeur de texte.

Ici, le nom donné au fichier n'est pas vraiment important, on aurait très bien pu décider de l'appeler `toto.c`, mais l'extension (le `.c`) permet de dire à notre machine que le texte que nous allons écrire n'est pas quelconque, mais que c'est bien du code C.

Une fois ce fichier ouvert dans un éditeur de texte de votre choix, je vous invite à copier-coller le code suivant:

```C
#include <stdio.h>

int main() {
	printf("Hello, World!\n");
	return 0;
}
```

Vous pouvez ensuite sauvegarder, et fermer le fichier.

### Compilation et execution

Le langage C est un langage compilé, ce qui signifie qu'avant que notre programme ne puisse s'éxécuter, nous devons le compiler en langage machine, compréhensible par notre ordinateur. C'est là que gcc intervient, c'est grâce à lui que nous allons pouvoir réaliser cette traduction.

Pour cela, dans le dossier où vous avez créé votre fichier `hello.c`, ouvrer un terminal (cf [Se déplacer dans le terminal](basic/shell/moving.md) et écriver:
```
$ gcc hello.c
```

Cela ne devrait pas faire grand chose dans votre terminal, mais vous devriez voir un fichier `a.out` apparaitre dans le dossier où vous vous trouvez.

En exécutant le ce fichier avec:
```
$ ./a.out
```

Vous obtiendrez donc:
```
Hello, World!
```

Bravo, vous avez réussi votre Hello world, vous avez écris votre premier programme en C.


### Analyse rapide
// Is it really important here ?
