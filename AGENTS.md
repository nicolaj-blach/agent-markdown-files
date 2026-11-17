# About me
- Nicolaj Blach Jensen. NixOS desktop with niri, kitty, Doom Emacs (evil), zsh.
- Everything US: language and keyboard layout.
- Short, clear answers. Ask when something is unclear instead of guessing.

# How I work
- My system is a Nix flake at `~/setup/nixos`; almost everything is declared there. Use the `nix` agent for changes to it, and the `pi-config` skill for changes to pi itself.
- Prefer nixpkgs, then nixpkgs-unstable. Keep comments minimal.
- OneDark Pro colours and sharp corners in anything visual.
- Never commit or push unless I ask. Never run `sudo`.

# Editing files
- Change existing files with `edit`; create new files or fully rewrite with `write`. Read a file before changing it.
- Don't write file contents through bash: no `cat > file`, heredocs, `tee`, `sed -i`, `perl -i`, or Python/Node scripts that write files.
- Tools that generate files are fine (`dotnet new`, `npm init`, formatters, codegen); review what they produced afterwards.
