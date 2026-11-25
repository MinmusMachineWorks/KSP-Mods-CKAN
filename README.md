# KSP-Mods-CKAN

CKAN metadata repository for Minmus Machine Works (Machine-Maker's KSP mods).

## Adding this repository

```
ckan repo add MinmusMachineWorks https://github.com/MinmusMachineWorks/KSP-Mods-CKAN/archive/main.tar.gz
```

Then install any mod listed here with `ckan install <identifier>`.

## Mods

Each mod has a folder named after its CKAN identifier, and each `<identifier>-<version>.ckan`
file in it is one release. The files are committed automatically by each mod's release workflow
(most use `.github/workflows/release-mod.yml` here).

The CKAN client reads every `*.ckan` file in the repository archive, whatever folder it is in, so
the folders are only for browsing.
