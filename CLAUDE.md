# riot-disco-web

Public website for the album RIOT (Riot Navarro, a character of tipsy-chat-personajes), served by GitHub Pages at
https://tuttobuio.github.io/riot/ from the `main` branch root.

Everything here is GENERATED — do not edit by hand. Source of truth: `tipsy-chat-personajes`,
`personajes/ideas/123-riot-navarro/disco/` (`plantilla.html`, `build_disco.py`, `tiempos_letra.py`, `arte/`, `audio/`).

Update:

    cd <tipsy-chat-personajes>/personajes/ideas/123-riot-navarro/disco
    python build_disco.py --web <this folder>
    cd <this folder> && git add -A && git commit -m "Update" && git push
