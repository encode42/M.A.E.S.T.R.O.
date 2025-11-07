# M.A.E.S.T.R.O. Mod Pack
A lightweight pack designed to provide you with the tools to test creations for [M.A.E.S.T.R.O.](https://youtu.be/G78AnHpIw5w), an incredible redstone machine that lets you play Note Block Songs (created with [Note Block Studio](https://noteblock.studio)) in vanilla Minecraft, and everything you'd want while attending the *Maestro's Musical Masterpieces* live event.

Everything is stripped down to its bare minimum, utilities and optimizations are baked-in for the smoothest experience, and the required world is provided and ready to use!

### Using the MAESTRO converter
Head to the [converter website](https://vladdesv.github.io/maestro/) and drag in your saved NBS file to convert it to a WorldEdit-compatible schematic file. Copy this file to the `config/WorldEdit/schematics` folder, found within the Minecraft profile's folder. In the M.A.E.S.T.R.O. world, run `//schem list` to display the available schematics, then click on the `[L]` icon to load it onto your clipboard. Run `tp 0 130 0`, followed by `//paste -a`, and the machine is ready to play!

In the future, this process should be automated.

### Server Pack
The server is designed to be stateless, everything that defines the event server is contained within this pack as well! Thanks to [Modrinth Servers](https://modrinth.com/servers), who provided the event server, for implementing an easy way to install and update server mod packs.

### Credits
- [C.O.N.D.U.C.T.O.R.](https://github.com/encode42/C.O.N.D.U.C.T.O.R.) is a server-side utility mod to tweak a few features.
- Mojang's note block sounds are included in stereo to achieve positionless playback.
