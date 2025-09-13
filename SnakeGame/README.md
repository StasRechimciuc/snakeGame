# SnakeGame

## Descriere proiect
SnakeGame este un proiect C++ care implementeaza jocul clasic Snake, unde jucatorul controleaza un sarpe ce se deplaseaza pe o tabla, mananca mere si creste in lungime. Scopul este sa obtii un scor cat mai mare fara sa lovesti marginile tablei sau corpul propriu.

## Regulile jocului Snake
- Sarpele se deplaseaza pe tabla in directia aleasa de jucator.
- Daca sarpele mananca un mar, creste in lungime.
- Jocul se termina daca sarpele loveste marginea tablei sau propriul corp.
- Scorul creste cu fiecare mar mancat.

## Tipuri de date noi declarate
- `struct Point` - reprezinta o pozitie pe tabla, avand coordonate x si y.
- `class Apple` - reprezinta un mar pe tabla, are o pozitie (`Point`).
- `enum class Direction` - reprezinta directia de deplasare a sarpelui (Top, Left, Right, Bottom).
- `class Snake` - reprezinta sarpele, are un vector de segmente (`Point`), numarul segmentelor, metode pentru miscare, crestere si obtinerea pozitiei.
- `class Board` - reprezinta tabla de joc, are latime si inaltime, metode pentru obtinerea dimensiunilor.
- `class GameEngine` - gestioneaza logica jocului, contine obiecte Apple, Snake si Board, metode pentru initializare si rulare.
- `class Painter` - responsabil pentru desenarea imaginilor si textului pe tabla, folosind coordonate de tip `Point`.

## Autor
Rechimciuc Stas DJ2401ro
