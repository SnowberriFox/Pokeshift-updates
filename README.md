# PokéShift, FoxTrot & Deeper Down updates

**Download the latest jar from [Releases](https://github.com/SnowberriFox/Pokeshift-updates/releases).** Early-access builds are marked pre-release.

This repo holds the release jars and the update files the mods read when the game starts, to tell players there's a newer
build (a toast on the title screen and a chat line with a link when they join):

- `update.json`: PokéShift (2.2.0-ea4.14 and newer)
- `foxtrot.json`: FoxTrot (the rhythm game, was PokéRhythm)
- `deeperdown.json`: Deeper Down (the dungeon)
- `snowberrilib.json`: SnowberriLib (needed by all three)

Since 3.0.0 they're four separate jars: SnowberriLib is always needed, the other three are pick-and-mix.

Since FoxTrot 4.0.0 there's also **`foxtrot-app-4.0.0.jar`**: FoxTrot on its own, no Minecraft needed (Java 21+, run it with
`java -jar foxtrot-app-4.0.0.jar`). It plays with Minecraft players through the FoxTrot Hub.

- `promos."1.21.1-latest"`: the newest build, early access included. EA players are told about it.
- `promos."1.21.1-recommended"`: the newest stable build. Everyone is told about it.
- `"1.21.1"`: a one-line note per version, shown with the notice.

(Same layout in every file.)

Keep the repo public so games can read the file. The mod's code lives in the main PokeShift repo.
