# OS X Lion theme for Gnome Shell

## installation:

```
cd /usr/share/themes && git clone https://github.com/maeve-oake/Lion
```

## nixos

place `Lion.nix` into your nixos directory, then link by adding this to configuration.nix:

```
environment.systemPackages = with pkgs; [
    (callPackage ./Lion.nix { })
];
```