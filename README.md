# **Dungeon Crawler**
## Introduction
**Gênero**: Fantasia ,RPG
- **Persspective**: Top-down
- **Plataform(s)**: PC, Nintendo Switch
- **Target Audience**: Jovens adultos, Adultos
- **Main influences**: Goblin Slayer, Grinmgar of fantasy and Ash
#### O objetivo, explorar dungeon e cidades para conseguir xp e items, estilo de batalha por turnos 
## Protagonista

## Item

## Historia
#### Após sair para ir buscar lenha, o protagonista retorna para casa e percebe que esta tudo muito calmo. Ao entrar em casa, ele é confrontado por uma visão aterradora:A família foi brutalmente assassinada. O que inicialmente começou como um dia normal tornou-se em um pesadelo, à medida que ele percebe que a morte de seus entes queridos.

## Links e Fontes
- https://goblin-slayer.fandom.com/wiki/Goblin_Slayer
- https://grimgar.fandom.com/wiki/Hai_to_Gensou_no_Grimgar_Wikia  
- https://hades.fandom.com/wiki/Hades_Wiki
- https://us.diablo3.blizzard.com/en-us/

```mermaid

flowchart TB

idl(( )) --- A
A{"A villager enters a house"}
A -- True --> B{"Their house"}
A -- False --> C{"The neighbours house"}
C -- True --> I{"Theres a witch"}
I -- True --> J{"She offers you a potion"}
J -- True --> K{"You drink it"}
J -- False --> L{"You refuse it"}
K -- True --> M{"You die"}
L -- True --> N{"She screams at you <br> and you run away"}
N -- True --> T{"You go home"}
N -- False --> U{"You go look for a tavern"}
U -- True --> V{"You find your drinking <br> buddies and follow them"}
U -- False --> X{"You fall down and hit your <br> head, you lost your <br> conscience"}
X -- True --> Z{"You wake up, its really late, <br> you go home"}
X -- False --> ZA{"You died and god <br> is looking at you, <br> he tells you <br> your family is dead aswell"}
ZA -- True --> ZB{"You join them and your <br> wife hugs you"}
ZB -- True --> ZD
ZA -- False -->ZC{"You run from them because <br> you are too ashamed you <br> couldnt protect <br> them"}
ZC -- True --> ZD{"THE END"}
T -- True --> D
B -- True --> D{"Your family was murdered <br> by goblins"}
D -- True --> E{"You get your chainsaw <br> from outside"}
D -- False --> F{"Your start crying in <br> dispair"}
E -- True --> G{"Go after the goblins"}
G -- True --> H{"You kill them all"}
H -- true --> O{"You mourn, your revenge <br> is complete"}
H -- False --> P{"You scream because <br> you avenged their lifes"}
O -- True --> R{"You go back home"}
P -- True --> R
R -- True --> Q{"You start cleaning the blood <br> and remains on the floor <br> and walls"}
Q -- True --> ZG{"You can handle it <br> ... somehow"}
ZG --True --> ZD
R -- False --> S{"You fall on your knees while <br> you think about your wife <br> and kids"}
S -- True --> ZF{"You cant handle it,<br> you go outside and kill <br> yourself"}
ZF -- True --> ZD

```