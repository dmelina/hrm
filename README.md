# Human Resource Machine

## Niveau 1

Mettre chaque éléments de **INBOX** (entrée) dans **OUTBOX** (sortie).

##### Jeu d'instructions

```
INBOX
OUTBOX
```
##### Mémoire

0 case

## Niveau 2

Prenez chaque éléments de **INBOX** (entrée) et déposer les tous dans **OUTBOX** (sortie).

##### Jeu d'instructions

```
INBOX
OUTBOX
JUMP
```

##### Mémoire

0 case


## Niveau 3

Ignore l'**INBOX** pour le moment, envoyer juste les 3 lettres suivantes dans **OUTBOX**: BUG.

##### Mémoire

6 cases mémoires avec des lettres.

##### Jeu d'instructions

```
INBOX
OUTBOX
COPYFROM
JUMP
```

### Niveau 40

Pour chaques objets dans **INBOX**, envoyez ces facteurs premiers dans **OUTBOX**, du plus petit au plus grand.

##### Mémoire

24 cases mémoires avec `0` sur 23

##### Jeu d'instructions

```
INBOX
OUTBOX
COPYFROM []
COPYTO []
ADD []
SUB []
BUMPUP []
BUMPDN []
JUMP
JUMPZ
JUMPN
```

