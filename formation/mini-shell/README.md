# Mini-shell en C

Exemple de structure pour ton code (à adapter) :

- `main.c` — boucle lecture ligne, dispatch des builtins (`cd`, `exit`).
- `parse.c` — découpage des arguments, gestion des `|`.
- `run.c` — `fork` / `execvp`, pipes, attente des processus.

Compile par exemple avec : `gcc -Wall -Wextra -o shell main.c parse.c run.c`

Ajoute `capture.png` dans ce dossier (capture de ton terminal avec quelques commandes tapées) pour l’image du README principal.
