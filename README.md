# Libft

Premier projet de l'école 42. Recoder des fonctions déjà existantes de la bibliothèque standard du C et d'autres 
fonctions annexes pouvant servir pour les projets suivants dans le cursus.

## Pour commencer

Ces instructions vous aideront à avoir une copie du projet et de pouvoir le faire marcher sur votre ordinateur.

### Prérequis

**Attention: A partir de maintenant, toutes les étapes (téléchargement, installation/compilation, exécution) seront à effectuer sur un terminal.**

#### Système d'exploitation

```
GNU/Linux, Mac OS X ou macOS Sierra
```

#### Téléchargement

Ce que vous devez faire pour télécharger les fichiers sources afin de pouvoir les compiler par la suite

```
git clone https://github.com/dcooray42/Libft.git [nom du PATH/dossier]
```

### Installation

Se placer dans le dossier dans lequel vous avez fait la copie des fichiers sources du projet puis rentrer la commande suivante

```
make
```
Plusieurs fichiers .o auront fait leur apparitions dans le dossier que vous avez cloné ainsi que la librairie statique

```
libft.a
```
### Suppression

Pour supprimer les fichiers objets .o généré lors de la création de la librairie

```
make clean
```

Pour supprimer les fichiers objets .o et la librairie libft.a

```
make fclean
```

Pour tout supprimer puis recompiler la librairie

```
make re
```

## Faire des tests

Aucun test n'est fourni avec ce projet. Toutefois vous pouvez créé un binaire avec vos propres fichiers sources et la 
librairie précédemment créé.

### Compilation avec le fichier libft.a

Aménager vos fichiers sources et headers dans un dossier unique de tel sorte à ce que la commande suivante fonctionne

```
gcc -Wall -Werror -Wextra -I [PATH du dossier cloné/includes] -L [PATH du dossier cloné] -lft *.c -o [nom de votre binaire]
```

## Liste des fonctions présentes dans la librairie libft.a

Voici la liste des fonctions présentes classées suivant leurs appartenances.

### Fonctions appartenant à la bibliothèque standard du C

* ft_memset
* ft_bzero
* ft_memcpy
* ft_memccpy
* ft_memmove
* ft_memchr
* ft_memcmp
* ft_strlen
* ft_strdup
* ft_strcpy
* ft_strncpy
* ft_strcat
* ft_strncat
* ft_strlcat
* ft_strchr
* ft_strrchr
* ft_strstr
* ft_strnstr
* ft_strcmp
* ft_strncmp
* ft_atoi
* ft_isalpha
* ft_isdigit
* ft_isalnum
* ft_isascii
* ft_isprint
* ft_toupper
* ft_tolower

### Fonctions annexes demandées dans la réalisation du projet et créées par la suite

* ft_atoif
* ft_atol
* ft_isxdigit
* ft_isspace
* ft_memalloc
* ft_memdel
* ft_strnew
* ft_strdel
* ft_strclr
* ft_striter
* ft_striteri
* ft_strmap
* ft_strmapi
* ft_strequ
* ft_strnequ
* ft_strsub
* ft_strjoin
* ft_strdeljoin
* ft_strtrim
* ft_strsplit
* ft_itoa
* ft_itoa_base
* ft_itoa_base_usigned
* ft_putchar
* ft_putstr
* ft_putendl
* ft_putnbr
* ft_putchar_fd
* ft_putstr_fd
* ft_putendl_fd
* ft_putnbr_fd
* ft_putwchar
* ft_putwstr
* ft_wstrlen
* ft_lstnew
* ft_lstdelone
* ft_lstdel
* ft_lstadd
* ft_lstiter
* ft_lstmap
* get_next_line
* ft_printf

## Note
115/100

## Auteur

* **Dimitri Cooray** - [Lien vers github](https://github.com/konamifox)
