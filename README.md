This repository lists the available mods and mod dependencies for
Death's Door.

To add your mod, make a pull request adding a [TOML][] file in the
`mods` directory, filled in with information about your mod (see existing files for examples of how to write the file). The file must
have the same name as the mod, and the SHA256 must match that of the
file you point to in Link.

To update your mod, make a pull request updating that same file.
You'll usually have to change at least the Link and SHA256.

[TOML]: https://toml.io