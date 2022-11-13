# nixfzf

```
A faster way to go through nixpkgs & install them,browse nixos options & home-manager options,
Usage: nixfzf [options] package/option

Options:
 -o             show nixos options
 -m             show home-manager options
 -n             show nixpkgs(default)
 -u -o          update nixos options
 -u -m          update home-manager options
 -u -n          update nixpkgs
 -h             help
```

# Install

```sh
wget https://raw.githubusercontent.com/strikerlulu/nixfzf/master/nixfzf
chmod +x nixfzf
./nixfzf
```

# Screenshots

![AdguardHome](./shots/1.png?raw=true)
![Vscode extensions](./shots/2.png?raw=true)
Options preview requires `yq` or `gojq`
![AdguardHome Options](./shots/3.png?raw=true)
