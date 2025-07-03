# Bukkit Install Action

This action installs Bukkit to the local Maven repo. This is useful for plugin development.

## Usage

This example step installs Bukkit 1.21.4.

```bash
- uses: charles25565/action-install-bukkit@main
  with:
    rev: 1.21.4
```

Once it is installed, you can use the local Maven repo and directly depend on Bukkit.
