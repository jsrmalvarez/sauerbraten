::: {align="center"}
[![Cube 2: Sauerbraten](docs/cube2logo.png)](http://sauerbraten.org/)
:::

Cube 2: Sauerbraten
===================

::: {.contents}
-   [**Links**](#links)
-   [**Documentation**](#documentation)
-   [**The Wiki**](#the_wiki)
-   [**Current Features**](#current_features)
    -   [Game Features](#game_features)
    -   [Engine Features](#engine_features)
-   [**Credits / Authors**](#credits_slash_authors)
-   [**License**](#license)
:::

Links
-----

First of all, welcome to Cube 2: Sauerbraten! To start off, if you are
looking for help with the game itself, refer to the
[**Documentation**](#documentation) below. Here are some places of
interest on the internet, which are related to *Cube / Cube 2:
Sauerbraten*.

-   [Cube and Cube 2 Engines](http://cubeengine.com/): Start Page for
    the Cube Engine series.
-   [Cube 2: Sauerbraten](http://sauerbraten.org/): The Sauerbraten FPS
    (First Person Shooter) Homepage.
-   [Quadropolis](http://quadropolis.us/): Online Cube Engine community,
    with user made maps, mods, and scripts.
-   [Sauerbraten IRC Channel](irc://irc.quakenet.org/sauerbraten):
    Online public chat with Cube developers, supporters and fans, via
    the [QuakeNet IRC Network](http://www.quakenet.org/).
-   [Cube Forums](http://cubeengine.com/forum.php): If after reading the
    documentation and wiki you still have any questions, you can try
    *searching* the forums. If your question isn\'t answered there, you
    can try posting to a relevant thread, or creating your own, being
    sure to supply a good description of your problem, and your
    operating system/hardware/software setup, while refraining from wild
    accusations.

Documentation
-------------

Cube 2: Sauerbraten is a multiplayer/singleplayer FPS freeware game
project. The source code for the engine used in these games is Open
Source (ZLIB licence, read the \"License\" section below carefully
before starting ANY kind of project based on this engine).

You will want to read (roughly this order):

-   [Game](docs/game.html): Information on gameplay.
-   [Config](docs/config.html): How to run the game, configure it for
    your machine, and extend it with scripts.
-   [Editing Tutorial](docs/editing.html): A guide to making maps.
-   [Editing Reference](docs/editref.html): Map making reference.
-   [Models](docs/models.html): How to put models into the game.
-   [History](docs/history.html): For seeing latest changes.
-   [Example RPG Game Information](docs/rpg.html): Information on
    running, building, or scripting the example RPG game.

The Wiki {#the_wiki}
--------

In addition to the documentation provided, the wiki has a lot of useful
information for working with the game and engine, contributed by the
community which elaborates and breaks alot of the information down into
more digestable chunks. This is just provided a short rundown of the
most useful topics to new players, and those looking for quick readable
information. For more go visit the [Cube
Wiki](http://cubeengine.com/wiki/).

-   [Beginners Guide](http://cubeengine.com/wiki/Beginners_Guide): Go
    through the steps to get up and running.
-   [Frequently Asked Questions](http://cubeengine.com/wiki/FAQ): Get
    the answers to some commonly asked questions, like; \"*The game runs
    very slowly, how can I fix it?*\", \"*Why is the game behaving
    strangely?*\", and \"*How do I fix the \'Hall of Mirrors\'
    effect?*\".
-   [Performance Guide](http://cubeengine.com/wiki/Performance_Guide):
    Things you can try to make the game either run faster or look better
    on your machine.
-   [Older Stuff](http://quadropolis.us/taxonomy/term/21): From
    Quadropolis.
-   Some [old](docs/dev/wikistuff.html) random documentation bits from
    our previous wiki that don\'t have a place yet.

Current Features {#current_features}
----------------

Cube 2: Sauerbraten is an open source project, and maintains constant
development, yet it is very feature-rich and playable as a game. What
follows is a list of the most prominent features.

### Game Features {#game_features}

-   Oldskool fast & intense gameplay (read: similar to Doom 2 / Quake
    1).
-   Many multiplayer gameplay modes, most in teamplay variants as well:
    deathmatch, instagib, efficiency, tactics, capture
    (domination/battlefield style), CTF (capture the flag), coop edit
    (!).
-   Masterserver & ingame server browser.
-   Lag-free gameplay experience.
-   Two singleplayer modes: DMSP (fight a monster invasion on any DM
    map), classic SP (progression driven SP like other games)
-   7 weapons tuned for maximum satisfaction: double barrelled shogun,
    rocket launcher, machine gun, rifle, grenade launcher, pistol, fist.

### Engine Features {#engine_features}

-   6 directional heightfield in octree world structure allowing for
    instant easy in-game geometry editing (even in multiplayer, coop
    edit).
-   Rendering engine optimized for high geometry throughput, supporting
    hardware occlusion culling and software precomputed conservative PVS
    with occluder fusion.
-   Lightmap based lighting with accurate shadows from everything
    including mapmodels, smooth lighting for faceted geometry, and fast
    compiles. Soft shadowmap based shadows for dynamic entities.
-   Pixel and vertex shader support, each model and world texture can
    have its own shader assigned. Supports normal and parallax mapping,
    specular and dynamic lighting with bloom and glow,
    environment-mapped and planar reflections/refractions, and
    post-process effects.
-   Robust physics written specifically for this world structure.
-   Loading of md2/md3/md5/obj/smd/iqm models for skeletal and vertex
    animated characters, weapons, items, and world objects. Supports
    animation blending, procedural pitch animation, and ragdoll physics
    for skeletally-animated characters.
-   Network library designed for high speed games, client/server network
    system.
-   Small but complete configuration/scripting language.
-   Simple stereo positional sound system.
-   Particle engine, supporting text particles, volumetric explosions,
    soft particles, and decals.
-   3D menu/GUI system, for in-world representation of choices.

Credits / Authors {#credits_slash_authors}
-----------------

::: {.credits}
Programming
:::

-   *Wouter \"Aardappel\" van Oortmerssen*: A lot of the general code,
    and the original concept and design. ([website](http://strlen.com/))
-   *Lee \"eihrul\" Salzman*: ENet networking library, \*nix ports, and
    a lot of the general code, especially rendering/lightmaps/physics
    related. ([website](http://sauerbraten.org/lee/))
-   *Mike \"Gilt\" Dysart*: General programming, especially
    editing/physics related.
-   *Robert \"baby-rabbit\" Pointon*: GUI, particle rendering, and movie
    recording code, MacOSX porting.
    ([website](http://www.fernlightning.com/))
-   *Quinton \"quin\" Reeves*: Bots/AI code. Asissts with community
    management, documentation/wiki, and development.
    ([website](http://www.redeclipse.net/))

::: {.credits}
Additional Code
:::

-   *Julian Mayer*: MacOSX ports.
-   *Adrian \"driAn\" Henke*: MD3 code.
-   *Jerry Siebe*: Geometry rendering optimisations.

::: {.credits}
Level Design
:::

-   *Kurt \"kdoom\" Kessler*: A bunch of DM/capture maps, k\_rpg1.
-   *Nieb*: academy, authentic, autumn, bt\_falls, c\_valley, complex,
    curvy\_castle, flagstone, garden, hallo, hashi, headroom, island,
    justice, nevil\_c, nmp4, nmp8, nmp9, ot, park, ra, shipwreck,
    turbine
-   *John \"metlslime\" fitzgibbons*: metl\* maps.
-   MitaMan: singleplayer episodes
-   With additional maps by: 4t3one, Aardappel, aftasardem, Ardelico,
    b4lkLu, BlikjeBier, Gabriele \"Blindabuser\" Magurno, Bryan
    \"KillHour\" Shalke, Chris\_0076, Cooper, Crap\_I\'m\_Dead,
    DairyKing, Destroyer, Doko, Drakker, driAn, Eleisa, Fanatic, Fatum,
    Fixxxer, flubz0r, Gilt, Gregor Koch, Hero, HeWho, JCDPC, jonlimle,
    Junebug, Justin, KaiserTodretter, Kal, KI113R, Kretren, Lazy
    \[HUN\], Majikal, Mayhem, MeatROme, Meister, MisanthropiX,
    mIscreant, PainKillAH, rabe, RatBoy, RaZgRiZ, Redon, rocknrol,
    schmutzwurst, sinsch, SirAlex, Skur, Snowy, SomeDude, sparr, staffy,
    Suicizer, SuperMan, t-chen, TomekGNO, TUX, viruz, voot, WahnFred,
    Windecker, wurfel, ZappaZ, Zeronic, and others.

::: {.credits}
Art / Content
:::

-   *John \"Geartrooper\" Siar*: Mr. Fixit, Ironsnout, RPG characters,
    monsters, new hudguns and vweps.
-   *Gabriele \"Blindabuser\" Magurno*: Logos, loading screen, announcer
    voices.
-   *MakkE*: Mapmodels, old hudguns, items.
-   *Dietmar \"dcp\" Pier*: Mapmodels, old hudguns.
-   *DarthVim*: Old hudguns.
-   *Nieb*: Textures, Mapmodels, Skyboxes.
-   *Sock*: The egyptian & tech texture sets
    ([website](http://www.planetquake.com/simland)).
-   *Iikka \"Fingers\" Keranen*: The ikbase ik2k texture sets
    ([website](http://www.digital-eel.com/surface)).
-   *Lunaran, Gibbie, Gregor Koch, Jésus \"aftasardem\" Maia, MitaMan,
    and philipk*: Normalmapped texture sets.
-   *SkiingPenguins*: Skyboxes.
-   Additional art by: metlslime (textures), Than (textures), Remedy
    Entertainment Ltd (textures), Seth & Ulrich Galbraith (GPL models),
    Brian \"EvilBastard\" Collins, Conrad, Magarnigal, Psionic, James
    Green, Andreas Möller, Ryan Butts & Jeramy Cooke (md2 models),
    KaiserTodretter (items), Tentus (mapmodels), Kurt Kessler
    (mapmodels), Philip Klevestav (textures), leileilol/OpenArena (GPL
    bullet hole decal).

::: {.credits}
Sound / Music
:::

-   *Marc \"Fanatic\" A. Pullen*: Soundtrack.

::: {.credits}
Other
:::

-   *Kristian \"sleepwalkr\" Duske*: website / messageboard, hosting,
    master server.
-   *Pushplay*: Documentation help.
-   *The SDL team*: For their libraries
    ([website](http://www.libsdl.org/)).

License
-------

The game is freeware, you may freely distribute the archive and/or
installer *unmodified* on any media. You may re-compress using different
archival formats suitable for your OS (i.e. zip/tgz/rpm/deb/dmg), any
changes beyond that require explicit permission from the developers.

You may play Cube 2: Sauerbraten for any purpose as long as you don\'t
blame the authors for any damages incurred.

If you want to produce new content with the Cube 2 Engine, you have to
be aware that the source code may be Open Source, but the game and the
media it consist of have their individual licenses and copyrights. This
means that you have roughly 3 options:

-   You may produce new content for the \"Sauerbraten\" game, for
    example as a *custom map* (.ogz/.cfg/textures etc). Contributing
    *content* to the original game is most welcome, and the most
    productive way of working with the community.
-   If you want to create your own gameplay beyond what you can do with
    a map, the best way to do this is as a \"mod\" (same as above, but
    with new executable that incorporates your gameplay), that *requires
    an existing install*, and *installs only the new files* you created
    in parallel to the existing files.
-   If you insist on making a standalone game based on Cube 2, do
    realize that *only the sourcecode* is yours to use freely (if you
    abide by the ZLIB license, see below), while the media is *not*. You
    can\'t simply redistribute the entire package with your modified
    files, as the majority of game media is not yours to use freely (it
    is made by many authors with a variety of licences and copyright
    restrictions). Unless you have explicit permission from the authors,
    or the readme says explicitly \"may be used for any purpose\" or
    similar language, it will be illegal to include in your standalone
    game based on the engine (you may not assume that just because a
    file has no explicit license, that it is free of copyright).
    Therefore, if you wish to produce a standalone game, be prepared to
    make many of the maps, models, textures, sounds etc from scratch
    yourself.

In this sense Cube 2: Sauerbraten is similar to games like Quake (its
code is Open Source, but its media is not), it is a game that is meant
to be added to, not copied and used as a template. Sauerbraten is not
meant to be a quick game creation kit, it is a game.

If you wish to use the source code (ZLIB license) in any way, read the
src/readme\_source.txt file carefully.
