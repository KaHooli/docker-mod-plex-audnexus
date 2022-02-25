# Audnex.us client - Docker mod for Plex

This mod adds [Audnex.us client plugin](https://github.com/djdembeck/Audnexus.bundle) to Plex, to be downloaded/updated during container start.

In plex docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/kahooli/plex-audnexus`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/kahooli/plex-audnexus|linuxserver/mods:plex-mod2`
