# saas

## Submodules

This repository uses git submodules for external dependencies.

### Included Submodules

| Path | Repository | Description |
|------|------------|-------------|
| `third_party/dyad` | https://github.com/dyad-sh/dyad.git | Dyad - External dependency |

### Initializing Submodules

After cloning this repository, initialize and update all submodules with:

```bash
git submodule update --init --recursive
```

To clone this repository with all submodules in one command:

```bash
git clone --recurse-submodules <repository-url>
```

### Updating Submodules

To update submodules to their latest commits:

```bash
git submodule update --remote --merge
```

## Third-Party Licenses

This project includes third-party code. See the [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) file for license information.