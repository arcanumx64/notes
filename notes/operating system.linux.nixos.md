---
id: k6fbx9qjun0gjam2nex5hj5
title: Nixos
desc: ''
updated: 1741800118655
created: 1741800095495
---

```sh
nix config show | grep experimental-features
```

```sh
nix flake show "github:arcanumx64/damathryxx64"
```

```sh
sudo nixos-rebuild switch --flake "github:arcanumx64/damathryxx64#nixos"
```

```sh
sudo nix-collect-garbage -d
```

```sh
sudo nix-store --gc
```

```sh
nix-env --list-generations
```

```sh
sudo nix-env --delete-generations old
```

```sh
sudo nixos-rebuild switch --rollback
```

```sh
nix-env -q
```

```sh
nix-env -iA nixpkgs.git
```

```sh
nix-env -e git
```

```sh
nixos-rebuild dry-run --flake .
```

```sh
nix config check
```

```sh
nix flake update
sudo nixos-rebuild switch --flake .#nixos
```
