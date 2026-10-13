# scoop-bucket

Scoop bucket for FD1x command-line tools.

## Usage

```powershell
scoop bucket add fd1x https://github.com/fd1x/scoop-bucket
scoop install sightline
```

## Maintenance

Every manifest in this repository is written by the release workflow of the tool it installs. Nothing here is edited by hand: a change to how a tool installs belongs in that tool's repository, and the next release rewrites the entry here.

## License

[Apache License 2.0](./LICENSE)
